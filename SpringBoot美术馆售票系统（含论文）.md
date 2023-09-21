## 218SpringBoot美术馆售票系统（含论文）

### 一、项目介绍

项目地址：http://javatip.cn/store/146.html

美术馆售票系统系统基于SpringBoot+Mybatis进行开发，系统分为管理员和普通用户两种角色。主要功能有：

管理员：

- 用户管理
- 美术馆管理
- 展览管理
- 门票管理
- 订单管理
- 订单退票

普通用户：

- 登录注册
- 美术馆收藏
- 美术馆预约
- 订票
- 我的订单
- 我的收藏
- 我的预约
- 我的评价

### 二、技术框架

- 后端：SpringBoot，Mybatis
- 前端：layui，jquery

### 三、安装教程

1. 用idea打开项目
2. 在idea中配置jdk环境
3. 配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 在application.yml文件中将数据库账号密码改成自己本地的
6. 默认上传图片在**F:/upload/**，如果没有F盘，则替换项目中的`file.properties` 和 `AppFileUtils.java`文件中的地址
7. 启动运行，浏览器输入 `http://localhost:8080` 进行访问。管理员账号密码 system/123456。普通用户账号密码 xiaoli/123456

更多项目请访问 http://javatip.cn

### 四、项目项目

![image-20230724203841479](http://image.javatip.cn/bysj/20230724203841.png)

![image-20230724204201926](http://image.javatip.cn/bysj/20230724204202.png)

![image-20230724204212039](http://image.javatip.cn/bysj/20230724204212.png)

![image-20230724204321223](http://image.javatip.cn/bysj/20230724204321.png)

![image-20230724204340861](http://image.javatip.cn/bysj/20230724204341.png)
