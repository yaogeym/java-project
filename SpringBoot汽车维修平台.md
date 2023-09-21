## 206SpringBoot汽车维修平台

### 一、项目介绍

项目地址：http://javatip.cn/store/116.html

汽车维修平台基于SpringBoot+Mybatis进行开发，通过gps定位实现优先推荐距离最近的修理厂。系统分为三种角色，用户浏览的前台网页，以及管理员和商家的管理系统，功能分别如下：

管理员：

- 前台用户管理
- 商家管理
- 维修点审核

商家：

- 登录注册
- 维修点管理
- 订单管理

顾客：

- 定位
- 注册登录
- 维修点查看
- 下单

### 二、技术框架

- 后端：SpringBoot，Mybatis
- 前端：layui

### 三、安装教程

1. 用idea打开项目
2. 在idea中配置jdk环境
3. 配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 在application.yml文件中将数据库账号密码改成自己本地的
6. 默认上传图片在**F:/upload/**，如果没有F盘，则替换项目中的`file.properties` 和 `AppFileUtils.java`文件中的地址
7. 启动运行，后台访问地址 `http://localhost:8080` 。管理员账号密码 system/123456，商家账号密码 shangjia/123456，前台访问地址 `http://localhost:8080/web`  顾客账号密码 yaoge/123456

更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20230718111857918](http://image.javatip.cn/bysj/20230718111858.png)

![localhost](http://image.javatip.cn/bysj/20230718112305.png)

![alhost](http://image.javatip.cn/bysj/20230718111944.png)

![image-20230718111538906](http://image.javatip.cn/bysj/20230718111539.png)

![image-20230718111605231](http://image.javatip.cn/bysj/20230718111605.png)

![image-20230718111808381](http://image.javatip.cn/bysj/20230718111808.png)
