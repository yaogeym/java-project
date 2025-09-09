## 422SpringBoot在线学习平台

### 一、项目介绍

项目地址：http://javatip.cn/store/810.html

在线学习平台是基于SpringBoot开发的，用于用户通过平台进行文本内容的学习，学习完后提交作业，后台统计各课程学习次数。具体功能如下：

前台用户：

- 注册登录
- 课程查看
- 课程搜索
- 课程详情
- 作业提交
- 查看公告

后台管理员：

- 用户管理
- 公告管理
- 课程分类管理
- 课程管理
- 作业查看
- 数据统计分析

### 二、技术框架

- 后端：SpringBoot，mybatis
- 前端：layui，jquery，thymeleaf

### 三、安装教程

1. 用idea打开项目
2. 在idea中配置jdk环境
3. 配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 在application.yml中将数据库账号密码改成自己本地的
6. 系统的静态资源存储在F盘，如果你的电脑没有F盘，则需要改成其他盘，具体位置在file.properties和FileConfig.java两个文件，将文件里面的F:/upload 改成你本地的即可。
7. 后台启动运行

>后台访问地址：http://localhost:8080，管理员账号密码：system/123456
>
>前台访问地址：http://localhost:8080/web，普通用户账号密码：zhb/123456


更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20240808152123552](http://image.javatip.cn/bysj/20240808152123.png)

![image-20240808152111407](http://image.javatip.cn/bysj/20240808152111.png)

![image-20240808152102038](http://image.javatip.cn/bysj/20240808152102.png)

![image-20240808152050914](http://image.javatip.cn/bysj/20240808152051.png)

![image-20240808152040993](http://image.javatip.cn/bysj/20240808152041.png)

![image-20240808151902964](http://image.javatip.cn/bysj/20240808151903.png)

![image-20240808151926118](http://image.javatip.cn/bysj/20240808151926.png)
