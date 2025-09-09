## 443SpringBoot电影订票系统

项目地址：http://javatip.cn/store/835.html

电影订票系统是由SpringBoot开发的，网站分为前台和后台，后台对电影院、影厅、排片进行管理，前台用户注册后选择观影城市，进行订票选座，选座后进行支付。

后台功能如下：

- 用户管理
- 地域管理
- 电影管理
- 影评管理
- 影院管理
- 影厅管理
- 排片管理
- 新闻资讯
- 用户订单管理

前台功能如下：

- 注册登录
- 首页
- 选择区域
- 选座购票
- 填写影评
- 查看资讯
- 账户充值
- 个人中心
- 我的订单
- 我的影评

### 二、技术框架

- 后端：SpringBoot，jpa
- 前端：jquery，bootstrap

### 三、安装教程

1. 用idea打开项目

2. 在idea中配置jdk环境

3. 配置maven环境并下载依赖

4. 新建数据库，导入数据库文件

5. 在application-dev.properties文件中将数据库账号密码改成自己本地的

6. 在application-dev.properties文件中将三个文件地址改成自己本地项目的地址（文件中地址写的是F:/movie/**）

7. 启动运行，

   ```
   后台地址：http://localhost:8080/system/login 账号密码 admin/123456
   前台地址：http://localhost:8080 账号密码 18888888888/123456
   ```


更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20241015101559674](http://image.javatip.cn/bysj/20241015101559.png)

![image-20241015101412801](http://image.javatip.cn/bysj/20241015101412.png)

![image-20241015101425810](http://image.javatip.cn/bysj/20241015101425.png)

![image-20241015101311063](http://image.javatip.cn/bysj/20241015101311.png)

![image-20241015101322194](http://image.javatip.cn/bysj/20241015101322.png)

![image-20241015101352516](http://image.javatip.cn/bysj/20241015101352.png)