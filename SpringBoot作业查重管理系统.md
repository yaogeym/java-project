## 328SpringBoot作业查重管理系统

### 一、项目介绍

项目地址：http://javatip.cn/store/209.html

作业查重管理系统基于SpringBoot+Mybatis开发，系统分为管理员、老师和学生三种角色，老师发布作业后，学生进行提交，发布的作业有两种类型，一种是在线的直接提交，另一种是文档的需要提交word文档，这里切记word类型的文档智能是doc结尾的，docx结尾的不可以。作业提交后，老师进行检测查重，并且批阅。

管理员：

- 院系管理
- 学生管理
- 教师管理
- 公告管理

教师：

- 学生管理
- 公告管理
- 课程管理
- 作业发布
- 作业查重
- 作业批阅
- 提交统计
- 成绩分析

学生：

- 公告查看
- 作业提交
- 成绩查看

### 二、技术框架

- 后端：SpringBoot，Mybatis
- 前端：layui，jquery

### 三、安装教程

1. 用idea打开项目
2. 在idea中配置jdk环境
3. 配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 在application.yml文件中将数据库账号密码改成自己本地的
6. 系统的静态资源存储在F盘，如果你的电脑没有F盘，则需要改成其他盘，具体位置在file.properties，AnswerController和FileConfig.java三个文件，将文件里面的F:/upload 改成你本地的即可。
7. 启动运行，访问 http://localhost:8080  , 管理员账号密码 system/123456 ，老师账号密码 mayun/123456，学生账号密码 xiaoli/123456。

更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20230811145015480](http://image.javatip.cn/bysj/20230811145015.png)

![image-20230811145424738](http://image.javatip.cn/bysj/20230811145424.png)

![image-20230811145313413](http://image.javatip.cn/bysj/20230811145313.png)

![image-20230811145325479](http://image.javatip.cn/bysj/20230811145325.png)

![image-20230811145445248](http://image.javatip.cn/bysj/20230811145445.png)
