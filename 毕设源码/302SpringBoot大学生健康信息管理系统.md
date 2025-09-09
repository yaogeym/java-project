## 302SpringBoot大学生健康信息管理系统

### 一、项目介绍

项目地址：http://javatip.cn/store/180.html

大学生健康信息管理系统基于SpringBoot+Mybatis开发，系统分为管理员，教师，学生三种角色。

管理员功能如下：

- 班级管理
- 学生管理
- 教师管理
- 新闻管理
- 体测数据管理

教师：

- 成绩分析
- 免测审核
- 测评题目
- 答题记录

学生：

- 我的体测成绩
- 健康日志
- 健康趋势分析
- 免测申请
- 测评答题

### 二、技术框架

- 后端：SpringBoot，Mybatis
- 前端：layui，echarts，jquery

### 三、安装教程

1. 用idea打开项目
2. 在idea中配置jdk环境
3. 配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 在application.yml文件中将数据库账号密码改成自己本地的
6. 系统的静态资源存储在F盘，如果你的电脑没有F盘，则需要改成其他盘，具体位置在file.properties和FileConfig.java两个文件，将文件里面的F:/upload 改成你本地的即可。
7. 启动运行，访问 http://localhost:8080  , 管理员账号密码 system/123456 ，教师账号密码 wxb/123456，学生账号密码 lm/123456

更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20230801154245093](http://image.javatip.cn/bysj/20230801154246.png)

![image-20230801154429355](http://image.javatip.cn/bysj/20230801154429.png)

![image-20230801154501224](http://image.javatip.cn/bysj/20230801154501.png)

![image-20230801154553113](http://image.javatip.cn/bysj/20230801154553.png)

![image-20230801154619027](http://image.javatip.cn/bysj/20230801154619.png)

![image-20230801154708300](http://image.javatip.cn/bysj/20230801154708.png)
