#### vagrant 基础命令

```
vagrant up //（启动虚拟机）
vagrant halt //（关闭虚拟机——对应就是关机）
vagrant suspend //（暂停虚拟机——只是暂停，虚拟机内存等信息将以状态文件的方式保存在本地，可以执行恢复操作后继续使用）
vagrant resume //（恢复虚拟机 —— 与前面的暂停相对应）
vagrant box remove centos6.6 //（移除box，其中centos6.6是box名）
vagrant destroy //（删除虚拟机，删除后在当前虚拟机所做进行的除开Vagrantfile中的配置都不会保留）
```