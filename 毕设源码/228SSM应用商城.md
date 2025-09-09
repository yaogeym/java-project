## 228SSM应用商城

### 一、项目介绍

项目地址：http://javatip.cn/store/169.html

应用商城使用SpringBoot+Mybatis进行开发，应用商城分为商城和后台管理系统，管理系统中上传应用，用户通过商城内搜索下载

前台主要功能：

- 注册登录 	 	
- 应用分类
- 应用浏览
- 应用搜索
- 应用下载
- 应用推荐
- 应用下载排行榜

后台功能：

- 顾客管理
- 分类管理
- 应用管理

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

![image-20230728142754203](http://image.javatip.cn/bysj/20230728142801.png)

![image-20230728143129764](http://image.javatip.cn/bysj/20230728143129.png)

![](http://image.javatip.cn/bysj/20230728143229.png)

![image-20230728143313163](http://image.javatip.cn/bysj/20230728143313.png)

![image-20230728143352729](http://image.javatip.cn/bysj/20230728143353.png)
