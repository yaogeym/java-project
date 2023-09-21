## 230SSM在线购药系统

### 一、项目介绍

项目地址：http://javatip.cn/store/174.html

在线购药系统使用SpringBoot+Mybatis进行开发，系统分为前台和后台，管理员通过后台管理药品，用户在前台进行购买药品。

前台主要功能：

- 注册登录 	 	
- 药品分类
- 药品浏览
- 药品搜索
- 药品购买
- 购物车
- 下单
- 我的订单

后台功能：

- 顾客管理
- 药品分类
- 药品管理
- 订单管理

### 二、技术框架

- 后端：Spring，SpringMvc，Mybatis
- 前端：bootstrap，jquery

### 三、安装教程

1. 用idea打开项目
2. 在idea中配置jdk环境
3. 配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 配置Tomcat8
6. 在jdbc.properties中将数据库账号密码改成自己本地的
7. 将压缩包中的upload文件夹移动到F盘下面
8. 启动运行，分别启动Tomcat下的前台项目和SpringBoot的后台项目

```
后台访问地址是 http://localhost:8080 账号密码是 admin 123456，
前台访问地址是 http://localhost:8080/fore/foreIndex 账号密码可用自己注册或者用前台用户名密码（yao/123456）
```

更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20230731155848818](http://image.javatip.cn/bysj/20230731155858.png)

![image-20230731160447258](http://image.javatip.cn/bysj/20230731160447.png)

![image-20230731160601890](http://image.javatip.cn/bysj/20230731160602.png)

![image-20230731160812854](http://image.javatip.cn/bysj/20230731160813.png)
