### 最青春数据库 和 育英数据库对应关系

#### 一、学生类
 * [学生信息表](#student)

#### 二、教师类
 * [教师信息表](#teacher)
 * [教师职位](#teacher_position)

#### 三、学校类
 * [学校信息](#school)
 * [校区信息](#campus)
 * [分校信息](#berkeley)
 * [班级信息](#class)
 * [教室信息](#classroom)
 * [教学楼信息](#building)
 * [专业信息](#speciality)

 #### 四、课程管理
 * [课程性质](#course_nature)
 * [课程信息](#course_info)

 #### 五、考试
 * [考试成绩等级](#exam_grade)
 * [成绩表现形式](#my_exam_level)

#### 六、院系资料
 * [学院信息](#institute)

<span id="student">学生</span>
> <table class="table table-bordered table-striped table-condensed">
	<tr>
		<th>最青春 - `my_student`</th>
		<th>育英 - `t_xj_studbaseinfo`</th>
		<th>备注</th>
	</tr>
	<tr>
		<td>student_id</td>
		<td>XH</td>
		<td>学生ID(学号)</td>
	</tr>
	<tr>
		<td>username</td>
		<td>XM</td>
		<td>姓名</td>
	</tr>
	<tr>
		<td>class_id</td>
		<td>SSBJ_ID</td>
		<td>班级ID</td>
	</tr>
	<tr>
		<td>email</td>
		<td>email</td>
		<td>邮箱</td>
	</tr>
	<tr>
		<td>sex</td>
		<td>XB</td>
		<td>性别</td>
	</tr>
	<tr>
		<td>birthday</td>
		<td>CSRQ</td>
		<td>出生日期</td>
	</tr>
	<tr>
		<td>enrol</td>
		<td>RXNJ</td>
		<td>入学年份</td>
	</tr>
	<tr>
		<td>LQZY</td>
		<td>LQZY</td>
		<td>录取专业</td>
	</tr>
	<tr>
		<td>SYDW</td>
		<td>SYDW</td>
		<td>生源单位(高中)</td>
	</tr>
	<tr>
		<td>password</td>
		<td>passwd</td>
		<td>密码</td>
	</tr>
	<tr>
		<td>address</td>
		<td>LXDZ</td>
		<td>联系地址</td>
	</tr>
</table>

<span id="teacher">教师信息表</span>
> <table class="table table-bordered table-striped table-condensed">
	<tr>
		<th>最青春 - `my_teacher`</th>
		<th>育英 - `t_zy_teacherinfo`</th>
		<th>备注</th>
	</tr>
	<tr>
		<td>teacher_id</td>
		<td>DM</td>
		<td>教师id</td>
	</tr>
	<tr>
		<td>institute_id</td>
		<td>SSDW_ID</td>
		<td>学院id</td>
	</tr>
	<tr>
		<td>username</td>
		<td>XM</td>
		<td>姓名</td>
	</tr>
	<tr>
		<td>birthday</td>
		<td>csrq_2</td>
		<td>生日</td>
	</tr>
	<tr>
		<td>duty</td>
		<td>ZC_ID</td>
		<td>职称id</td>
	</tr>
	<tr>
		<td>tel</td>
		<td>bysj</td>
		<td>电话</td>
	</tr>
	<tr>
		<td>email</td>
		<td>email</td>
		<td>邮箱</td>
	</tr>  
	<tr>
		<td>sex</td>
		<td>XB</td>
		<td>性别(1 男  2 女)</td>
	</tr>
	<tr>
		<td>explains</td>
		<td>gzjl</td>
		<td>备注</td>
	</tr>
	<tr>
		<td>GH</td>
		<td>GH</td>
		<td>工号</td>
	</tr>
	<tr>
		<td>password</td>
		<td>passwd</td>
		<td>密码</td>
	</tr>
	<tr>
		<td>address</td>
		<td>address</td>
		<td>常用联系地址</td>
	</tr>
</table>

<span id="teacher_position">教师职位</span>
> <table class="table table-bordered table-striped table-condensed">
	<tr>
		<th>最青春 - `my_teacher_duty`</th>
		<th>育英 - `t_zy_professioninfo`</th>
		<th>备注</th>
	</tr>
	<tr>
		<td>DM</td>
		<td>DM</td>
		<td>ID</td>
	</tr>
	<tr>
		<td>MC</td>
		<td>MC</td>
		<td>职称</td>
	</tr>
	<tr>
		<td>sys_flag</td>
		<td>sys_flag</td>
		<td>？</td>
	</tr>
</table>

<span id="school">学校信息</span>
> <table class="table table-bordered table-striped table-condensed">
	<tr>
		<th>最青春 - ``</th>
		<th>育英 - `t_zy_schoolinfo`</th>
		<th>备注</th>
	</tr>
	<tr>
		<td>-</td>
		<td>DM</td>
		<td>ID</td>
	</tr>
	<tr>
		<td>-</td>
		<td>ZWMC</td>
		<td>名称</td>
	</tr>
	<tr>
		<td>-</td>
		<td>YWMC</td>
		<td>学校英文名称</td>
	</tr>
	<tr>
		<td>-</td>
		<td>SJ</td>
		<td>院长</td>
	</tr>
	<tr>
		<td>-</td>
		<td>ZGBM</td>
		<td>主管部门</td>
	</tr>
	<tr>
		<td>-</td>
		<td>DZ</td>
		<td>地址</td>
	</tr>
	<tr>
		<td>-</td>
		<td>YB</td>
		<td>邮政编码</td>
	</tr>
</table>

<span id="campus">校区信息</span>
> <table class="table table-bordered table-striped table-ondensed">
	<tr>
		<th>最青春 - `my_school_area`</th>
		<th>育英 - `t_zy_school_area`</th>
		<th>备注</th>
	</tr>
	<tr>
		<td>-</td>
		<td>MC</td>
		<td>-</td>
	</tr>
	<tr>
		<td>-</td>
		<td>BZ</td>
		<td>-</td>
	</tr>
	<tr>
		<td>-</td>
		<td>JC</td>
		<td>-</td>
	</tr>
</table>

<span id="berkeley">分校信息</span>
> <table class="table table-bordered table-striped table-ondensed">
	<tr>
		<th>最青春 - `my_department`</th>
		<th>育英 - `t_zy_departmentinfo`</th>
		<th>备注</th>
	</tr>
	<tr>
		<td>title</td>
		<td>ZWMC</td>
		<td>分院名称</td>
	</tr>
</table>

<span id="class">班级信息</span>
> <table class="table table-bordered table-striped table-ondensed">
	<tr>
		<th>最青春 - `my_class`</th>
		<th>育英 - `t_xj_classinfo`</th>
		<th>备注</th>
	</tr>
	<tr>
		<td>id</td>
		<td>BJDM</td>
		<td>信息ID</td>
	</tr>
	<tr>
		<td>pid</td>
		<td>ZY_ID</td>
		<td>-</td>
	</tr>
	<tr>
		<td>title</td>
		<td>BJMC</td>
		<td>名称</td>
	</tr>
	<tr>
		<td>num</td>
		<td>BJRS</td>
		<td>班级人数</td>
	</tr>
	<tr>
		<td>grade</td>
		<td>NJ</td>
		<td>年级</td>
	</tr> 
	<tr>
		<td>FDY</td>
		<td>fdyname</td>
		<td>辅导员id</td>
	</tr>
	<tr>
		<td>XZ</td>
		<td>XZ</td>
		<td>学制</td>
	</tr>
	<tr>
		<td>BZRphone</td>
		<td>BZRphone</td>
		<td>班主任联系电话</td>
	</tr>
	<tr>
		<td>FDYphone</td>
		<td>FDYphone</td>
		<td>辅导员联系电话</td>
	</tr>
</table>

<span id="classroom">教室信息</span>
> <table class="table table-bordered table-striped table-ondensed">
	<tr>
		<th>最青春 - `my_classroom`</th>
		<th>育英 - `t_zy_classroominfo`</th>
		<th>备注</th>
	</tr>
	<tr>
		<td>classroom_id</td>
		<td>DM</td>
		<td>ID</td>
	</tr>
	<tr>
		<td>building_id</td>
		<td>SZWZ</td>
		<td>教学楼id</td>
	</tr>
	<tr>
		<td>title</td>
		<td>MC</td>
		<td>教室名称</td>
	</tr>
	<tr>
		<td>num</td>
		<td>RL</td>
		<td>-</td>
	</tr>
	<tr>
		<td>BH</td>
		<td>DM</td>
		<td>主键id 就是 DM，看是否需要</td>
	</tr>
</table>

<span id="building">教学楼信息</span>
> <table class="table table-bordered table-striped table-ondensed">
	<tr>
		<th>最青春 - `my_building`</th>
		<th>育英 - `t_zy_building`</th>
		<th>备注</th>
	</tr>
	<tr>
		<td>building_id</td>
		<td>DM</td>
		<td>ID</td>
	</tr>
	<tr>
		<td>title</td>
		<td>MC</td>
		<td>教学楼名称</td>
	</tr>
	<tr>
		<td>school_id</td>
		<td>SZWZ</td>
		<td>教室名称</td>
	</tr>
	<tr>
		<td>KYJS</td>
		<td>RL</td>
		<td>-</td>
	</tr>
	<tr>
		<td>status</td>
		<td>status</td>
		<td>-</td>
	</tr>
	<tr>
		<td>BH</td>
		<td>DM</td>
		<td>主键id 就是 DM，看是否需要</td>
	</tr>
</table>

<span id="speciality">专业信息</span>
> <table class="table table-bordered table-striped table-ondensed">
	<tr>
		<th>最青春 - `my_speciality`</th>
		<th>育英 - `t_zy_specialityinfo`</th>
		<th>备注</th>
	</tr>
	<tr>
		<td>id</td>
		<td>DM</td>
		<td>信息id</td>
	</tr>
	<tr>
		<td>pid</td>
		<td>ZGBM</td>
		<td>院系id</td>
	</tr>
	<tr>
		<td>title</td>
		<td>ZWMC</td>
		<td>专业名称</td>
	</tr>
	<tr>
		<td>XZ</td>
		<td>XZ</td>
		<td>学制</td>
	</tr>
	<tr>
		<td>BH</td>
		<td>DM</td>
		<td>主键id 就是 DM，看是否需要</td>
	</tr>
</table>

<span id="course_nature">课程性质</span>
> <table class="table table-bordered table-striped table-ondensed">
	<tr>
		<th>最青春 - `my_choose_cate`</th>
		<th>育英 - `t_jh_lsort1info`</th>
		<th>备注</th>
	</tr>
	<tr>
		<td>id</td>
		<td>DM</td>
		<td>id</td>
	</tr>
	<tr>
		<td>title</td>
		<td>MC</td>
		<td>名称</td>
	</tr>
	<tr>
		<td>flag</td>
		<td>sys_flag</td>
		<td>-</td>
	</tr>
	<tr>
		<td>-</td>
		<td>english</td>
		<td>英文名称</td>
	</tr>
</table>

<span id="course_info">课程信息</span>
> <table class="table table-bordered table-striped table-ondensed">
	<tr>
		<th>最青春 - `my_course_info`</th>
		<th>育英 - `t_jh_setlessoninfo`</th>
		<th>备注</th>
	</tr>
	<tr>
		<td>course_id</td>
		<td>DM</td>
		<td>课程id</td>
	</tr>
	<tr>
		<td>department_id</td>
		<td>CDDW_ID</td>
		<td>开课系所id</td>
	</tr>
	<tr>
		<td>title</td>
		<td>ZWMC</td>
		<td>名称</td>
	</tr>
	<tr>
		<td>credit</td>
		<td>ZXF</td>
		<td>学分</td>
	</tr>
	<tr>
		<td>period</td>
		<td>ZXS</td>
		<td>学时</td>
	</tr>
</table>

<span id="exam_grade">考试成绩等级</span>
> <table class="table table-bordered table-striped table-ondensed">
	<tr>
		<th>最青春 - `my_exam_grade`</th>
		<th>育英 - `t_cj_levelsort`</th>
		<th>备注</th>
	</tr>
	<tr>
		<td>id</td>
		<td>DM</td>
		<td>id</td>
	</tr>
	<tr>
		<td>level_id</td>
		<td>LB</td>
		<td>对应登记id</td>
	</tr>
	<tr>
		<td>title</td>
		<td>Text</td>
		<td>名称</td>
	</tr>
	<tr>
		<td>status</td>
		<td>sys_flag</td>
		<td>-</td>
	</tr>
	<tr>
		<td>SX</td>
		<td>xx</td>
		<td>分数上限</td>
	</tr>
	<tr>
		<td>XX</td>
		<td>sx</td>
		<td>分数下限</td>
	</tr>
	<tr>
		<td>english</td>
		<td>english</td>
		<td>英文名称</td>
	</tr>
</table>

<span id="my_exam_level">成绩表现形式</span>
> <table class="table table-bordered table-striped table-ondensed">
	<tr>
		<th>最青春 - `my_exam_level`</th>
		<th>育英 - `t_cj_format`</th>
		<th>备注</th>
	</tr>
	<tr>
		<td>id</td>
		<td>DM</td>
		<td>id</td>
	</tr>
	<tr>
		<td>title</td>
		<td>MC</td>
		<td>-</td>
	</tr>
	<tr>
		<td>status</td>
		<td>sys_flag</td>
		<td>-</td>
	</tr>
</table>

<span id="institute">学院信息</span>
> <table class="table table-bordered table-striped table-ondensed">
	<tr>
		<th>最青春 - `my_institute`</th>
		<th>育英 - `t_zy_instituteinfo`</th>
		<th>备注</th>
	</tr>
	<tr>
		<td>id</td>
		<td>DM</td>
		<td>id</td>
	</tr>
	<tr>
		<td>title</td>
		<td>ZWMC</td>
		<td>名称</td>
	</tr>
	<tr>
		<td>type</td>
		<td>School_Area</td>
		<td>-</td>
	</tr>
	<tr>
		<td>YZ</td>
		<td>YZ</td>
		<td>院长</td>
	</tr>
	<tr>
		<td>SJ</td>
		<td>SJ</td>
		<td>书记</td>
	</tr>
</table>