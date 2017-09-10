# -failed-to-complete-gradle-execution
Android studio 报错 failed to complete gradle execution 远程主机关闭了一个现有的连接


解决方案：

Android studio没有在项目中找到你本地的jdk安装路径，所以默认了自带jre的路径。

将项目中的studio 自带的jre换成你本地的jdk路径就ok了。

