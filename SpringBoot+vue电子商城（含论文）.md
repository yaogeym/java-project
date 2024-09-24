## 418SpringBoot+vue电子商城（含论文）

### 一、项目介绍

项目地址：http://javatip.cn/store/804.html

电子商城系统充分考虑了管理员和普通用户两类角色的不同需求，为他们提供了量身定制的功能模块。普通用户可以通过简单的注册流程轻松进入商城，在琳琅满目的商品中自由查找自己心仪的产品。一旦找到心仪的商品，用户还可以与在线客服进行实时沟通，了解产品的详细信息，解决购物过程中的疑问。当然，购买产品和查看订单等功能也是必不可少的，为用户提供了完整的购物体验。

电子商城系统是由SpringBoot+vue开发的前后端分离的项目，系统分为用户前台和管理员后台，项目中使用了websocket技术实现在线客服实时通讯功能，具体角色及功能如下：

前台：

- 注册登录
- 系统首页（商品、关于、通知、系统介绍）
- 电子产品查询
- 通知公告
- 留言板
- 在线客服
- 购物车
- 评论商品
- 我的订单
- 我的地址
- 收藏商品

后台：

- 个人中心
- 用户管理
- 产品分类管理
- 产品管理
- 留言回复
- 系统介绍
- 在线客服
- 轮播图管理
- 关于我们
- 通知公告
- 订单管理

### 二、技术框架

- 后端：SpringBoot，mybatis，websocket
- 前端：vue，elementui

### 三、安装教程

1. 用idea打开项目
2. 在idea中配置jdk环境
3. 配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 在application.yml中将数据库账号密码改成自己本地的
6. 找到**FileController**，大概第70行的位置，将 F:\\bysj\\2024路径替换为你本地的项目存放路径，路径中不要使用中文
7. 启动运行

>前台和后台分别使用两个浏览器进行访问，同一个浏览器访问可能会造成token失效
>
>后台路径地址：localhost:8080/springbootgqon2/admin/dist/index.html  账号密码：admin/123456
>前台路径地址：localhost:8080/springbootgqon2/front/dist/index.html  账号密码：lr/123456
>
>注：本系统已将vue前端打包到后台项目中，如需二次开发请使用node版本v12.22.12下载依赖进行二开！


更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20240806142230390](http://image.javatip.cn/bysj/20240806142230.png)

![image-20240806142046881](http://image.javatip.cn/bysj/20240806142047.png)

![image-20240806142105907](http://image.javatip.cn/bysj/20240806142106.png)

![image-20240806142139177](http://image.javatip.cn/bysj/20240806142139.png)

![image-20240806142151012](http://image.javatip.cn/bysj/20240806142151.png)

![image-20240806142215209](http://image.javatip.cn/bysj/20240806142215.png)

![image-20240806142319624](http://image.javatip.cn/bysj/20240806142319.png)
