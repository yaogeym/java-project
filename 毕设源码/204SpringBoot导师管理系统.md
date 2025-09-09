## 204SpringBoot导师管理系统

### 一、项目介绍

项目地址：http://javatip.cn/store/113.html

导师管理系统SpringBoot+Mybatis进行开发，主要实现了导师与学生之间的双向选择，任务布置，知道交流，评价等功能。系统除了教师和学生还有超级管理员，总共三种角色。

超级管理员：

- 用户管理（学生/教师）
- 专业管理

教师：

- 查看选择自己的学生
- 与学生交流
- 评价学生
- 给学生布置任务
- 查看学生研究成果
- 添加指导记录
- 为学生的研究成果评分

学生：

- 查看教师信息
- 选择导师
- 与教师交流
- 评价导师
- 上传研究成果
- 查看指导记录

### 二、技术框架

- 后端：SpringBoot，Mybatis
- 前端：bootstrap

### 三、安装教程

1. 用idea打开项目
2. 在idea中配置jdk环境
3. 配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 在application.yml文件中将数据库账号密码改成自己本地的
6. 启动运行，浏览器输入 `http://localhost:8080` 即可访问。管理员账号密码 system/123456，教师账号密码 ymh/123456，学生账号密码 lxl/123456

更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20230717225130132](http://image.javatip.cn/bysj/20230717225130.png)

![image-20230717225209186](http://image.javatip.cn/bysj/20230717225209.png)

![image-20230717225233817](http://image.javatip.cn/bysj/20230717225233.png)

![image-20230717225257640](http://image.javatip.cn/bysj/20230717225257.png)

![image-20230717225312719](http://image.javatip.cn/bysj/20230717225312.png)

![image-20230717225326812](http://image.javatip.cn/bysj/20230717225326.png)
