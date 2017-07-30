PHP代码规范
==========

## 编码规范

### 必须在系统中安装的软件

* php-cs-fixer

### 必须在IDE中安装的插件

* editorconfig，可以在不同编辑器中同步代码规范设置，比如不管用atom、phpstorm或者sublime，只要项目根目录有.editorconfig文件，都可以同步

* php-cs-fixer，规则设置成symfony，可以自动格式化PHP代码

### 关于强制规范检查

默认情况下，当系统初始化后(app/console app:init)，会自动安装一个git的pre-push hook，该hook会在每次git push之前检查代码规范，若不通过则终止push过程并给出提示

### php编码规范

* 缩进用4个空格

* 参考[symfony规范](https://github.com/djoos/Symfony2-coding-standard)

* 数组的key要用下划线方法，不要用驼峰法

### symfony路由编写规范

* 缩进用4个空格

* routing.yml中路由的path非变量部分都用下划线方法，变量用驼峰法，因为变量会变成Controller的参数，因为PHP变量是驼峰法。

  ```yaml
  goods_category:
      path: goods_category/group/{groupCode}
      defaults: { _controller: AppBundle:Category:index }
  ```

### twig编码规范

* 缩进用2个空格

* twig里的命名(如方法名、变量名或者属性名)一般都要用下划线方法，不要用驼峰法。

  特殊情况：

  * twig中生成路由时，若遇到路由变量，则需要用驼峰法
  
    ```html
    <a href="{{ path('goods_category', {groupCode: 'product'}) }}">产品分类</a>
    ```
    
    ```php
    class CategoryController extends BaseController
    {
        public function indexAction(Request $request, $groupCode)
        {
            //$groupCode对应routing.yml中的路由变量
        }
    }
    ```
  
  * twig中生成路由时，若不是路由变量，而是get或post参数，则还是用下划线方法
  
    ```html
    <a href="javascript:;" class="btn btn-primary btn-sm " data-url="{{ path('goods_category_create', {'group_code': group_code}) }}" data-toggle="modal" data-target="#modal">新增分类</a>
    ```
    
    ```php
    class CategoryController extends BaseController
    {
        public function createAction(Request $request)
        {
          $groupCode = $request->query->get('group_code');
          //group_code对应twig声明的get参数
        }
    }
    ```

### 其他规范

* html,twig,less,css,js,jsx这些语法的缩进都用2个空格，如果editorconfig没有效果，请自行配置好自己的IDE

## 业务规范

### 异常处理

异常都发生在程序错误中断时，用户在正常使用系统时不应该看到异常提示，所以异常文案都是给开发者看的，一般都用英文，不推荐用中文。

抛异常时，需要按照异常类型抛出不同的异常类，比如

```php
# 当用户提交的数据，缺少必要字段时，抛出InvalidArgumentException异常
if (!ArrayToolkit::requireds($fields, array('name', 'code'))) {
    throw new InvalidArgumentException('Missing required fields of category');
}
```

注意： 由于用户端提示由前端控制，比如上述样例中，用户在表单里面没有输入必填的字段时，应当在前端做校验并用正常的语言（中文）提示用户。如果前端校验失效或者用户非法提交，则会看到英文的提示。

### 异常类

不要直接用系统的异常类，要用包装过的异常类

* src/Biz下面要用 Biz\Common\Exception\xxxxException
