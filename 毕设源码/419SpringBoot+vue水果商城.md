## 419SpringBoot+vue水果商城

### 一、项目介绍

项目地址：http://javatip.cn/store/805.html

电子商城系统是由SpringBoot+vue开发的前后端分离的项目，系统分为前台和后台，前台用于用户购买商城中的水果，后台用于管理员和商家对水果进行管理。具体角色及功能如下：

前台：

- 注册登录
- 水果查看
- 公告查看
- 购物车管理
- 水果收藏
- 水果评论
- 收货地址管理
- 我的订单

商家：

- 个人中心

- 公告查看
- 水果管理
- 评价管理
- 订单管理
- 销量统计

管理员：

- 个人中心
- 公告类型管理
- 水果分类管理
- 公告管理
- 水果管理
- 评价管理
- 订单管理
- 销量统计
- 用户管理
- 商家管理
- 轮播图管理

### 二、技术框架

- 后端：SpringBoot，mybatis
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
>后台路径地址：http://localhost:8080/shuiguozaixianxiaoshou/admin/dist/index.html  管理员账号密码：admin/123456，商家账号密码：drf/123456
>前台路径地址：http://localhost:8080/shuiguozaixianxiaoshou/front/index.html  账号密码：wm/123456
>
>注：本系统已将vue前端打包到后台项目中，如需二次开发请使用node版本v12.22.12下载依赖进行二开！


更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20240822174944302](http://image.javatip.cn/bysj/20240822174944.png)

![image-20240806174838591](http://image.javatip.cn/bysj/20240806174839.png)

![image-20240806174909850](http://image.javatip.cn/bysj/20240806174910.png)

![image-20240806174928111](http://image.javatip.cn/bysj/20240806174928.png)

![image-20240806174611341](http://image.javatip.cn/bysj/20240806174611.png)

![image-20240806174555746](http://image.javatip.cn/bysj/20240806174555.png)

![image-20240806174750451](http://image.javatip.cn/bysj/20240806174750.png)
