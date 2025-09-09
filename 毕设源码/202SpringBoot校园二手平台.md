## 202SpringBoot校园二手平台

### 一、项目介绍

项目地址：http://javatip.cn/store/108.html

校园二手平台使用SpringBoot+Mybatis进行开发，系统分为前台和后台，前台进行商品浏览购买，后台进行数据得管理。

前台功能如下：

- 注册登录
- 商品浏览
- 分类查看商品
- 商品搜索
- 购物车
- 商品下单
- 模拟支付

后台功能如下：

- 用户管理
- 分类管理
- 商品管理
- 订单管理
- 订单明细

### 二、技术框架

- 后端：SpringBoot，Mybatis
- 前端：layui

### 三、安装教程

1. 用idea打开项目

2. 在idea中配置jdk环境

3. 配置maven环境并下载依赖

4. 新建数据库，导入数据库文件

5. 本项目前后台使用了两个模块，在digital-system项目和digital-transaction项目下的application.yml文件中将数据库账号密码改成自己本地的

6. 将下载下来的压缩包里的upload文件夹房到电脑的F盘中

7. 一、分别启动前台、后台项目，DigitalSystemApplication和DigitalTransacationApplication

    建议前台和后台分别使用两种浏览器进行访问

    在浏览器中访问后台：http://localhost:8081

    后台账户 xiaoli 123456

    浏览器中访问前台地址  http://localhost:8080

    可以自己注册账户或者  使用账户  yaoge  123456 进行登录

更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20230714163538765](http://image.javatip.cn/bysj/20230714163545.png)

![host](http://image.javatip.cn/bysj/20230714163637.png)

![image-20230714163819046](http://image.javatip.cn/bysj/20230714163819.png)

![image-20230714163838184](http://image.javatip.cn/bysj/20230714163838.png)

![image-20230714163850130](http://image.javatip.cn/bysj/20230714163850.png)

![image-20230714163906475](http://image.javatip.cn/bysj/20230714163906.png)
