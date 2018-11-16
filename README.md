一个在window 上运行 tail -f 的工具

比如java后台读取手机传过来的实时坐标信息。在tomcat 里查看要加很多配置，而且有很多无关的信息输出。为了方便查看，你可以用代码写日志，到location.txt 文件

然后运行 tail -f location.txt 就可以动态的查看点位信息输出了，和linux 一样
