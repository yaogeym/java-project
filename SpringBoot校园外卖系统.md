## 133SpringBoot校园外卖系统

### 一、项目介绍

项目地址：http://javatip.cn/store/159.html

校园外卖系统使用SpringBoot+Mybatis进行开发，校园外卖平台，分为前台和后台，后台使用springboot开发，前台使用ssm开发，启动的时候先启动后台springboot项目，然后启动前台，前台需要配置tomcat进行访问，

前台主要功能：

- 注册登录 	 	

- 美食分类
- 美食浏览
- 美食搜索
- 美食购买
- 购物车
- 下单
- 我的订单
- 商品评价

后台功能：

- 顾客管理
- 分类管理
- 商品管理
- 评论管理
- 订单管理
- 订单发货

### 二、技术框架

- 后端：SpringBoot，Mybatis
- 前端：layui，jquery

### 三、安装教程

1. 用idea打开项目
2. 在idea中配置jdk环境
3. 配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 配置Tomcat8
6. 在application.yml文件和jdbc.properties中将数据库账号密码改成自己本地的
7. 启动运行，分别启动Tomcat下的前台项目和SpringBoot的后台项目

```
后台访问地址是 http://localhost 账号密码是 admin 123456，
前台访问地址是 http://localhost:8080/fore/foreIndex 账号密码可用自己注册或者用前台用户名密码（yao/123456）
```

更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20230726214747343](http://image.javatip.cn/bysj/20230726214748.png)

![image-20230726214930539](http://image.javatip.cn/bysj/20230726214930.png)

![image-20230726214941849](http://image.javatip.cn/bysj/20230726214942.png)

![image-20230726215040064](http://image.javatip.cn/bysj/20230726215040.png)

![image-20230726215054059](http://image.javatip.cn/bysj/20230726215054.png)

![image-20230726215111166](http://image.javatip.cn/bysj/20230726215111.png)
