## 411SpringBoot大学生时间管理系统（英文版）

### 一、项目介绍

项目地址：http://javatip.cn/store/347.html

大学生时间管理系统内容采用全英文展示，主要是学生用来管理自己在哪些事情上花费的时间以及统计。也可以通过系统来记录心得体验。系统提供用户注册功能，注册后就可以进行记录。主要功能如下：

- 注册登录
- 首页展示（统计任务数量，学生任务量，进入任务信息）
- 时间管理
- 心得记录
- 各时间花费时间比例

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

>访问地址：http://localhost:8080，注册后登录，或使用默认账号密码登录：wx/123456


更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20240729151850556](http://image.javatip.cn/bysj/20240729151850.png)

![image-20240729151912391](http://image.javatip.cn/bysj/20240729151912.png)

![image-20240729151926998](http://image.javatip.cn/bysj/20240729151927.png)

![image-20240729152142829](http://image.javatip.cn/bysj/20240729152142.png)

![image-20240729152154937](http://image.javatip.cn/bysj/20240729152155.png)
