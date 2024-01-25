## 166SpringBoot在线点餐系统

### 一、项目介绍

项目地址：http://javatip.cn/store/285.html

在线点餐系统使用SpringBoot+Mybatis进行开发，系统主要实现了用户在线点餐，管理员备餐等功能，流程完整实现用户点餐功能。

管理员主要功能如下：

- 分类管理

- 餐品管理
- 添加餐品
- 订单管理
- 接单
- 用户管理
- 个人中心

普通用户：

- 注册登录

- 菜单浏览
- 购物车管理
- 在线下单
- 确认订单送达
- 个人中心

### 二、技术框架

- 后端：SpringBoot，Mybatis
- 前端：jquery，thymeleaf

### 三、安装教程

1. 用idea打开项目
2. 在idea中配置jdk环境
3. 配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 在application.yml文件中将数据库账号密码改成自己本地的
6. 配置图片路径，下载后的源码文件夹中有一个images的文件夹，将这个文件夹移动F盘下的upload文件夹下。如果没有F盘，则随便移动到一个盘下面，然后将源码 FileUpload 文件和 MyWebAppConfigurer 文件下的路径改成你的images文件夹的路径。
7. 启动运行，浏览器输入 http://localhost:8080 进行访问，管理员账号密码：admin/123456，普通用户账号密码：user/123456

更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20231225152155945](http://image.javatip.cn/bysj/20231225152156.png)

![image-20231225152050737](http://image.javatip.cn/bysj/20231225152051.png)

![image-20231225152110918](http://image.javatip.cn/bysj/20231225152111.png)

![image-20231225152137295](http://image.javatip.cn/bysj/20231225152137.png)

![image-20231225151532407](http://image.javatip.cn/bysj/20231225151727.png)
