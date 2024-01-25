## 152SpringBoot求职招聘网站

### 一、项目介绍

项目地址：http://javatip.cn/store/269.html

求职招聘网站使用SpringBoot+Mybatis进行开发，系统分为管理员和求职者和招聘者三种角色，系统分为前台和后台，后台主要是管理员进行数据管理，前台由求职者和招聘者进行浏览，发布职位，投递简历等。

管理员主要功能如下：

- 用户管理
- 职位类别管理
- 职位管理
- 公司管理

求职者：

- 注册登录
- 完善简历
- 投递简历
- 投递记录
- 浏览职位
- 查看公司

招聘者：

- 完善公司信息
- 发布职位
- 发布记录
- 收到的简历
- 预览简历
- 筛选简历
- 面试通知

### 二、技术框架

- 后端：SpringBoot，Mybatis
- 前端：jquery，easyui

### 三、安装教程

1. 用idea打开项目

2. 在idea中配置jdk环境

3. 配置maven环境并下载依赖

4. 新建数据库，导入数据库文件

5. 在application-dev.properties文件中将数据库账号密码改成自己本地的

6. 在application-dev.properties文件中将图片路径写成你本地的路径，注意路径中不要带中文

7. 在application-dev.properties文件中将邮件发送配置改成自己的，需要在邮箱中开启，具体可百度搜索

8. 启动运行

    > 前台地址：http://localhost:8080/home/index/index
    >
    > 账号密码可自行注册，或者用默认的，求职者：832858782@qq.com/12345678，招聘者：2250173789@qq.com/12345678
    >
    > 后台地址：http://localhost:8080/admin/system/login
    >
    > 账号密码：admin/123456

更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20231213215103865](http://image.javatip.cn/bysj/20231213215103.png)

![image-20231213214941186](http://image.javatip.cn/bysj/20231213215014.png)

![image-20231213214957134](http://image.javatip.cn/bysj/20231213215017.png)

![image-20231213214928360](http://image.javatip.cn/bysj/20231213215019.png)

![image-20231213214859719](http://image.javatip.cn/bysj/20231213215022.png)
