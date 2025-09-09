## 174SpringBoot+vue校园二手交易平台

### 一、项目介绍

项目地址：http://javatip.cn/store/295.html

校园二手交易平台是由SpringBoot+vue开发的前后端分离的项目，系统分为管理员和普通用户两种角色，系统主要目的是校园内的闲置物品进行交易，用户可注册后进行发布闲置物品或出售闲置物品。

管理员：

- 用户管理
- 用户封号
- 闲置管理
- 下架闲置

用户：

- 注册登录
- 闲置搜索
- 分类查看
- 闲置浏览
- 留言回复
- 发布闲置
- 下架闲置
- 我的购物车
- 购买
- 购买记录
- 出售记录
- 收获地址管理

### 二、技术框架

- 后端：SpringBoot，mybatis
- 前端：vue，elementui

### 三、安装教程

1. 用idea打开后端项目backend
2. 在idea中配置jdk环境
3. 配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 在application.properties中将数据库账号密码改成自己本地的
6. 将下载后的项目，有个静态文件夹里面的xmtp文件夹移动到自己的盘符
7. 在application.properties中文件路径 userFilePath=F:\\upload\\xmtp 改为上一步的路径
8. 后台启动运行
9. 安装nodejs环境
10. 在idea中打开前端项目frontend，使用`npm install`命令，下载依赖
11. 下载完成后输入启动命令启动前台项目，`npm run serve`

>访问地址：http://localhost:8081，管理员账号密码：admin/123456，普通用户注册，或者用 18888888888/123456


更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20240123190538642](http://image.javatip.cn/bysj/20240123190538.png)

![image-20240123184017460](http://image.javatip.cn/bysj/image-20240123184017460.png)

![image-20240123190558048](http://image.javatip.cn/bysj/20240123190558.png)

![image-20240123190610315](http://image.javatip.cn/bysj/20240123190610.png)

![image-20240123190735558](http://image.javatip.cn/bysj/20240123190735.png)

![image-20240123190746563](http://image.javatip.cn/bysj/20240123190746.png)

![image-20240123190645639](http://image.javatip.cn/bysj/20240123190645.png)

![image-20240123190654547](http://image.javatip.cn/bysj/20240123190654.png)
