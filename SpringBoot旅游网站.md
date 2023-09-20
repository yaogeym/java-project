## 113SpringBoot旅游网站

### 一、项目介绍

项目地址：http://javatip.cn/store/102.html

旅游网站是由SpringBoot+Mybatis开发的，旅游网站分为前台和后台，前台为用户浏览，后台进行数据管理

后台功能如下：

- 注册用户统计
- 用户管理
- 旅游路线管理
- 景点管理
- 酒店管理
- 留言管理
- 攻略管理
- 车票管理
- 保险管理
- 订单管理
- 数据统计分析

前台功能如下：

- 注册登录
- 旅游路线查看、预定
- 景点查看、预定
- 酒店查看、预定
- 车票查看、预定
- 保险查看、预定
- 攻略查看
- 我的留言
- 我的订单
- 订单付款、撤销

### 二、技术框架

- 后端：SpringBoot，Mybatis
- 前端：layui，echarts

### 三、安装教程

1. 用idea打开项目

2. 在idea中配置jdk环境

3. 配置maven环境并下载依赖

4. 新建数据库，导入数据库文件

5. 在application.yml文件中将数据库账号密码改成自己本地的

6. 静态资源路径修改，找到application.yml中的**uploadPath: xxx\target\classes\static**按以下方式修改

    ```shell
    # xxx表示你本地项目的根目录，从磁盘开始复制到项目名字
    # 比如我本地的项目在F:\biyesheji\travel,那么xxx在用F:\biyesheji\travel替换
    ```

7. 启动运行

    ```shell
    前台
    地址：http://localhost/index
    账号：user  密码：123456
    
    后台
    地址：http://localhost/login
    账号：admin  密码：123456
    ```

更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20230712113241548](http://image.javatip.cn/bysj/20230712113241.png)

![image-20230712113302939](http://image.javatip.cn/bysj/20230712113303.png)

![image-20230712113447568](http://image.javatip.cn/bysj/20230712113447.png)

![image-20230712113359883](http://image.javatip.cn/bysj/20230712113359.png)

![image-20230712113424089](http://image.javatip.cn/bysj/20230712113424.png)

![image-20230712113523220](http://image.javatip.cn/bysj/20230712113523.png)
