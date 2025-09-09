## 318SpringBoot+vue生产管理系统

### 一、项目介绍

项目地址：http://javatip.cn/store/195.html

生产管理系统基于SpringBoot+vue进行开发，系统分为系统管理员，生产管理员和厂长三种角色。

管理员功能：

- 用户管理
- 部门管理
- 角色管理

生产管理员：

- 物料查看
- 产品查看
- 产量查看
- 订单查看
- 生产计划管理

厂长：

- 物料管理
- 产品管理
- 产品登记查看
- 订单管理
- 生产计划查看
- 产量统计

### 二、技术框架

- 后端：SpringBoot，Mybatis
- 前端：vue，elementui，echarts

### 三、安装教程

1. 解压目录后，前台项目在product-ui目录中，idea打开product-ui目录，后台项目在product-system目录中，新开一个idea窗口打开product-system目录
2. 在后台idea中配置jdk环境
3. 在后台配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 在application.yml文件中将数据库账号密码改成自己本地的
6. 在idea中进入前台文件夹product-ui。在idea底部打开**Terminal**，然后分别输入命令**npm install** 下载依赖。等到进度条走完后在**Terminal**中分别输入命令 **npm run serve**启动前台项目（需要安装node环境，本机测试用的node版本为 v12.22.12）。
7. 启动后台springboot的项目
8. 管理员账号密码 system/123456，生产管理与账号密码 ls/123456，厂长账号密码 lc/123456

更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20230807134708366](http://image.javatip.cn/bysj/20230807134708.png)

![image-20230807134633389](http://image.javatip.cn/bysj/20230807134633.png)

![image-20230807134621284](http://image.javatip.cn/bysj/20230807134621.png)

![image-20230807134606304](http://image.javatip.cn/bysj/20230807134606.png)

![image-20230807134452939](http://image.javatip.cn/bysj/20230807134546.png)

![image-20230807134729013](http://image.javatip.cn/bysj/20230807134729.png)
