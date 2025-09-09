## 413SpringBoot电子书店（含论文）

### 一、项目介绍

项目地址：http://javatip.cn/store/349.html

电子书店是由SpringBoot开发的，旨在通过集成先进的信息技术，为书店提供一套全面、高效、稳定的管理解决方案。该系统需满足前台商城和管理后台的双向需求，确保书店运营流程的顺畅与用户体验的优化。系统分为前台和后台，前台商城应提供丰富的书籍信息展示，浏览书籍详情并加入购物车。购物车功能应支持书籍的增删改查，以及结算时选择支付方式、填写收货地址等。此外，用户应能够查看自己的订单信息，以便随时掌握订单动态。在管理后台方面，系统需提供书籍分类管理功能，支持管理员对书籍分类进行增删改查操作，确保书籍信息的规范与准确。

具体功能如下:

前台用户：

- 注册登录
- 首页书籍
- 书籍详情
- 购物车
- 我的订单

后台管理员：

- 用户管理
- 书籍分类管理
- 书记管理
- 订单管理
- 订单发货

### 二、技术框架

- 后端：SpringBoot，jpa
- 前端：bootstrap，jquery，thymeleaf

### 三、安装教程

1. 用idea打开项目
2. 在idea中配置jdk环境
3. 配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 在application.yml中将数据库账号密码改成自己本地的
6. 系统的静态资源存储在F盘，如果你的电脑没有F盘，则需要改成其他盘，具体位置在file.properties和FileConfig.java两个文件，将文件里面的F:/upload 改成你本地的即可。
7. 后台启动运行

>后台访问地址：http://localhost:8080/mall/admin/toLogin.html，管理员账号密码：admin/123456
>
>前台访问地址：http://localhost:8080/mall，用户账号密码：user/123456

### 四、项目截图

![image-20240801153952598](http://image.javatip.cn/bysj/20240801153952.png)

![image-20240801154115529](http://image.javatip.cn/bysj/20240801154115.png)

![image-20240801154059423](http://image.javatip.cn/bysj/20240801154059.png)

![image-20240801154135705](http://image.javatip.cn/bysj/20240801154135.png)

![image-20240801154152938](http://image.javatip.cn/bysj/20240801154153.png)

![image-20240801154215534](http://image.javatip.cn/bysj/20240801154215.png)
