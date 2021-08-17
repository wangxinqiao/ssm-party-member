# ssm党员管理系统

## 项目介绍
````
党员管理系统,分为管理员、干部、党员三种角色；


#### 管理员主要功能包括：

党员信息管理：新增党员、批量新增党员、党员信息查询；

干部信息管理：新增干部、批量新增干部、干部信息查询；

部门信息管理：新增部门、部门信息查询；

课程信息管理：新增课程、课程信息查询；

课件信息管理：文档管理、视频管理；

党务工作管理：党务工作讨论；

党费工作管理：党费查询、党费缴纳；

公告信息管理：新增公告、公告信息查询；

#### 干部主要功能包括：

课程文件管理：上传课程视频、查询上传的视频、上传课程文档、查询上传的文档；

党务工作管理：新增党务工作、党务工作信息查询；

党费工作管理：党费查询、党费缴纳；

个人信息管理：

#### 党员主要功能包括：

课程查询：查看课程信息；

文件查询：在线课程视频、在线课程文件；

党务工作：回复党务工作信息；

党费缴纳：党费查询、党费缴纳；

公告查询：查看公告；

个人信息：修改个人信息；
````
源码获取：[ **点此获取** ](http://www.shuyue.fun/index.php?type=productinfo&id=232)

## 环境需要
````

1.运行环境：最好是java jdk 1.8，我们在这个平台上运行的。其他版本理论上也可以。

2.IDE环境：IDEA，Eclipse,Myeclipse都可以。推荐IDEA;

3.tomcat环境：Tomcat 7.x,8.x,9.x版本均可

4.硬件环境：windows 7/8/10 1G内存以上；或者 Mac OS；

5.是否Maven项目: 否；查看源码目录中是否包含pom.xml；若包含，则为maven项目，否则为非maven项目

6.数据库：MySql 5.7版本；
````

## 技术栈
````

1. 后端：Spring SpringMVC MyBatis

2. 前端：JSP+Vue+Bootstrap+jQuery
````

## 使用说明
````

1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并导入项目的sql文件；

2.使用IDEA/Eclipse/MyEclipse导入项目，Eclipse/MyEclipse导入时，若为maven项目请选择maven;
若为maven项目，导入成功后请执行maven clean;maven install命令，配置tomcat，注：tomcat中配置的路径必须为/learn，否则会有问题；

3. 将项目中jdbc.properties配置文件中的数据库配置改为自己的配置，然后运行；

4. 访问地址：http://localhost:8080/learn/preLogin.html
````

## 运行截图
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/230027_8abfa205_9600114.jpeg "WX20210524-150125@2x.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/230113_1427eacd_9600114.jpeg "WX20210524-150857@2x.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/230121_e8c7bd2c_9600114.jpeg "WX20210524-150944@2x.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/230201_345a6a7e_9600114.jpeg "WX20210524-150959@2x.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/230211_84628690_9600114.jpeg "WX20210524-151032@2x.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/230219_00b3851f_9600114.jpeg "WX20210524-151048@2x.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/230227_06554cf4_9600114.jpeg "WX20210524-151101@2x.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/230236_eded8df5_9600114.jpeg "WX20210524-151115@2x.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/230246_f7e70695_9600114.jpeg "WX20210524-151133@2x.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/230300_3a52e949_9600114.jpeg "WX20210524-151204@2x.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/230307_e959288a_9600114.jpeg "WX20210524-151230@2x.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/230317_e903d588_9600114.jpeg "WX20210524-151310@2x.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/230325_cea2b9bf_9600114.jpeg "WX20210524-151322@2x.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/230333_819869f3_9600114.jpeg "WX20210524-151331@2x.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/230341_eda52e22_9600114.jpeg "WX20210524-151344@2x.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/230353_b15a6bc6_9600114.jpeg "WX20210524-151414@2x.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/230402_2c159f74_9600114.jpeg "WX20210524-151555@2x.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/230410_06a3726b_9600114.jpeg "WX20210524-151608@2x.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/230418_d9b3f2fb_9600114.jpeg "WX20210524-151623@2x.jpeg")