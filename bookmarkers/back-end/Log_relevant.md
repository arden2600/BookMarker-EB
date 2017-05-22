## Log Relevant Bookmark<br>
记录在开发过程中遇到的与日志相关内容的书签。<br>

### Log4j<br>
整合在项目中使用到的log4j日志处理相关的内容。包括log4j的详细配置，设置日志大小，日志数量，日志文件名称等等。<br>
* [log4j.xml配置详解](http://willow-na.iteye.com/blog/347340)<br>
   挺详细的介绍log4j和log4j的配置使用。包括不同标签标示的内容等等。<br>
* [Log4j的扩展-支持设置最大日志数量的DailyRollingFileAppender](http://www.cnblogs.com/rembau/p/5201001.html)<br>
   介绍了log4j中的RollingFileAppender和DailyRollingFileAppender。并拓展了DailRFA,使得他支持设置每个日志文件的大小以及日志文件的数量。<br>
### Apache Tomcat Log<br>
在tomcat服务器启动和运行过程中，服务器也有日志输出。那么tomcat对自身日志输出记录是如何控制的呢，下面就对一些常用的日志文件控制进行整合记录。以及apache服务器中日志管理的内容整合。<br>
* [Tomcat输出catalina.out的大小控制](http://blog.csdn.net/attagain/article/details/38639007)<br>
  介绍了如何控制tomcat默认生成的日志文件catlina.out，结合cronolog工具控制日志文件大小以及文件名称。<br>
* [限制apache日志文件access.log大小方法详解](http://www.111cn.net/sys/Windows/52909.htm)<br>
  介绍了Apache服务器中自带工具rotatelogs工具如何控制输出日志文件大小等设置。<br>

### Linux Log<br>
在Linux系统中，也有自带的控制日志管理文件的机制，即使用**logrorate**来对Linux系统的日志进行总管。<br>

* [Linux日志文件总管——logrotate](https://linux.cn/article-4126-1.html)<br>
  非常详细的说明了如何使用logrorate对Linux系统的日志进行管理和操作。<br>
* [Linux中利用logrotate来对log文件进行循环管理](http://www.linuxidc.com/Linux/2012-02/53940.htm)<br>