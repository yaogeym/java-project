## 157SpringBoot+vue养老服务管理系统

### 一、项目介绍

项目地址：http://javatip.cn/store/275.html

养老服务管理系统是由SpringBoot+vue开发的前后端分离的项目，系统分为管理员和志愿者两种种角色，也可以通过管理员账号配置所需要的其他角色。

管理员功能如下：

- 用户管理
- 角色管理
- 老人管理
- 服务管理
- 服务记录
- 活动管理
- 志愿者招募
- 志愿者请假

志愿者功能如下：

- 老人管理
- 服务记录
- 活动管理
- 志愿者招募查看
- 我的请假

### 二、技术框架

- 后端：SpringBoot，jpa
- 前端：vue，elementui

### 三、安装教程

1. 用idea打开项目
2. 在idea中配置jdk环境
3. 配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 在aged-stage-api下的application.yml中将数据库账号密码改成自己本地的
6. 启动redis服务，在aged-stage-api下的application.yml中将redis账号密码改成自己本地的
7. 安装nodejs环境
8. 在idea中打开前端项目，使用`yarn install`命令，下载依赖，如果报错找不到 `yarn` ，那就是没有安装`yarn`，使用命令 `npm install -g yarn` 先安装 `yarn`，然后再运行`yarn install` 下载依赖。
9. 下载完成后输入启动命令启动前台项目，`yran run dev`
10. 后台启动运行

>访问地址：http://localhost:8080，管理员账号密码：admin/123456，志愿者账号密码：wm/123456


更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20231218163812799](http://image.javatip.cn/bysj/20231218163812.png)

![image-20231218163758847](http://image.javatip.cn/bysj/20231218163758.png)

![image-20231218163743615](http://image.javatip.cn/bysj/20231218163743.png)

![image-20231218163720284](http://image.javatip.cn/bysj/20231218163720.png)

![image-20231218163544613](http://image.javatip.cn/bysj/20231218163659.png)
