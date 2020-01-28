# HTTP协议和Tomcat服务器

## HTTP协议

  超文本传输协议(HTTP),WEB开发重要环节,规定了浏览器和服务器之间的通信协议

###   HTTP的请求(GET)

   请求行

- GET请求方式
- 服务器的URL,传递参数
  - 参数数据格式 k=v
  - 多个参数&分割
- 协议版本

   请求头

​    包含了指导服务器的信息

![](img\http_请求(get).jpg)



###   HTTP的请求(POST)

  请求行

- 请求方式POST
- 提交服务器URL
- 协议版本

  请求头

​     指导性信息

  请求体

- 提交参数
- 数据格式 k=v

![](img\http_请求(post).jpg)

### HTTP的响应

  响应行

* 协议版本
* 状态码

  响应头

​    指导客户端浏览器信息

  响应体

​    页面的正文部分

![](\\img\http_响应.jpg)



## Tomcat软件的目录结构

![](img\tomcat目录结构.jpg)



## IDEA绑定Tomcat

![](img\idea1.jpg)

![](img\idea2.jpg)

![](img\idea3.jpg)

![](img\idea4.jpg)

![](img\idea5.jpg)



## IDEA创建WEB项目

![](img\idea6.jpg)

![](img\idea7.jpg)



## WEB项目发布到Tomcat

![](img\idea8.jpg)

![](img\idea9.jpg)

![](img\idea10.jpg)

![](img\idea11.jpg)

![](img\idea12.jpg)

![](img\idea13.jpg)



## Tomcat中的项目结构

![](img\idea14.jpg)



## Servlet程序快速入门

  Servlet是运行在服务器端的Java程序,Servlet也是JavaEE十三规范中的一个规范

  规范理解为就是接口interface

  实现步骤:

* 创建类,实现接口Servlet
* 重写接口中的全部的抽象方法
* 通过Tomcat服务器,运行实现类,web.xml编写配置文件