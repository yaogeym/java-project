## 154SpringBoot宿舍管理系统

### 一、项目介绍

项目地址：http://javatip.cn/store/272.html

宿舍管理系统使用SpringBoot+Mybatis进行开发，系统分为管理员、宿管和学生三种角色。

管理员主要功能如下：

- 用户管理
- 宿管管理
- 宿舍管理

宿管：

- 学生查询
- 报修单处理
- 入校登记
- 离校登记
- 宿舍评分
- 访客管理

学生：

- 申请报修
- 入校登记
- 离校登记
- 宿舍评分查看

### 二、技术框架

- 后端：SpringBoot，JPA
- 前端：jquery，bootstrap

### 三、安装教程

1. 用idea打开项目

2. 在idea中配置jdk环境

3. 配置maven环境并下载依赖

4. 新建数据库，导入数据库文件

5. 在application-dev.properties文件中将数据库账号密码改成自己本地的

6. 在application-dev.properties文件中将图片路径写成你本地的路径，注意路径中不要带中文

7. 在application-dev.properties文件中将邮件发送配置改成自己的，需要在邮箱中开启，具体可百度搜索

8. 启动运行，浏览器输入http://localhost:8080进行访问，管理员账号密码：admin/123456，宿管账号密码：1001/123456，学生账号密码：20151001/123456


更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20231214140706892](http://image.javatip.cn/bysj/20231214140707.png)

![image-20231214145937966](http://image.javatip.cn/bysj/20231214145938.png)

![image-20231214150026211](http://image.javatip.cn/bysj/20231214150026.png)

![image-20231214150145298](http://image.javatip.cn/bysj/20231214150145.png)
