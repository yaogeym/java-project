## 434SpringBoot+vue汽车配件销售系统（含论文）

### 一、项目介绍

项目地址：http://javatip.cn/store/337.html

汽车配件销售系统是基于SpringBoot+mybatis开发，系统分为前台和后台，后台负责对配件等信息进行管理，前台用于购买配件，查看资讯等，功能如下：

后台：

- 站点管理
- 用户管理
- 资讯管理
- 配件分类
- 配件管理
- 订单管理

前台：

- 注册登录
- 资讯查看
- 公告查看
- 配件购买
- 配件收藏
- 我的地址管理
- 我的购物车
- 我的订单

### 二、技术框架

- 后端：SprinBoot，mybatis
- 前端：vue，elementui

### 三、安装教程

1. 用idea打开后端项目（总共有三个项目，一个后台，一个前台的前端项目，一个后台的前端项目。用idea打开三个窗口）
2. 在idea中配置jdk环境
3. 配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 在application.yml中将数据库账号密码改成自己本地的
6. 启动后台运行
7. idea打开前端项目**client-admin**，使用命令**npm install**下载依赖，然后使用命令 **npm run dev**运行。
8. idea打开前端项目**client-home**，使用命令**npm install**下载依赖，然后使用命令 **npm run serve**运行。

>前台和后台分别使用两个浏览器进行访问，同一个浏览器访问可能会造成token失效
>
>后台路径地址：localhost:8080  管理员账号密码：admin/123456
>前台路径地址：localhost:8081  账号密码：wm123/123456
>
>多项目请访问 http://javatip.cn

### 四、项目截图

![image-20240826165343057](http://image.javatip.cn/bysj/20240826165343.png)

![image-20240826165315760](http://image.javatip.cn/bysj/20240826165315.png)

![image-20240826165326720](http://image.javatip.cn/bysj/20240826165326.png)

![image-20240826165642464](http://image.javatip.cn/bysj/20240826165643.png)

![image-20240826165710939](http://image.javatip.cn/bysj/20240826165711.png)
