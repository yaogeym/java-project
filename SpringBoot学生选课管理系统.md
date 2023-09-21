## 324SpringBoot学生选课管理系统

### 一、项目介绍

项目地址：http://javatip.cn/store/204.html

学生选课管理系统基于SpringBoot+Mybatis开发，分科三门语文，数学，英语主课外，物理和历史必选一个，化学，生物，政治，地理任选两个，还可以选择一些体育课外活动，系统分为管理员，学生和老师三种角色。

管理员：

- 班级管理
- 学生管理
- 教师管理
- 新闻公告
- 课程管理
- 退课

教师：

- 新闻查看
- 课程查看
- 我的课程被选记录

学生：

- 新闻查看
- 选课
- 我的选课
- 退课

### 二、技术框架

- 后端：SpringBoot，Mybatis
- 前端：layui，jquery

### 三、安装教程

1. 用idea打开项目
2. 在idea中配置jdk环境
3. 配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 在application.yml文件中将数据库账号密码改成自己本地的
6. 系统的静态资源存储在F盘，如果你的电脑没有F盘，则需要改成其他盘，具体位置在file.properties和FileConfig.java两个文件，将文件里面的F:/upload 改成你本地的即可。
7. 启动运行，访问 http://localhost:8080  , 管理员账号密码 system/123456 ，教师账号密码 wxb/123456，学生账号密码 ly/123456

更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20230809135634535](http://image.javatip.cn/bysj/20230809135635.png)

![image-20230809135240981](http://image.javatip.cn/bysj/20230809135241.png)

![image-20230809135311953](http://image.javatip.cn/bysj/20230809135312.png)

![image-20230809135612737](http://image.javatip.cn/bysj/20230809135612.png)
