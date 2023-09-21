## 319SpringBoot+vue水质检测与绩效分析平台

### 一、项目介绍

项目地址：http://javatip.cn/store/196.html

水质检测与绩效分析平台基于SpringBoot+vue进行开发，系统分为系统管理员和机构检测人员两种角色。

管理员功能：

- 用户管理
- 企业管理
- 检测点管理
- 检测任务发布
- 检测申请审批
- 检测数据管理
- 检测统计

检测机构人员：

- 个人信息管理
- 检测任务申请
- 经纬度地址拾取
- 检测位置上报
- 检测数据上报
- 检测历史数据

### 二、技术框架

- 后端：SpringBoot，Mybatis
- 前端：vue，elementui，echarts

### 三、安装教程

1. 解压目录后，前台项目在detection-ui目录中，idea打开detection-ui目录，后台项目在detection-system目录中，新开一个idea窗口打开detection-system目录
2. 在后台idea中配置jdk环境
3. 在后台配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 在application.yml文件中将数据库账号密码改成自己本地的
6. 在idea中进入前台文件夹detection-ui。在idea底部打开**Terminal**，然后分别输入命令**npm install** 下载依赖。等到进度条走完后在**Terminal**中分别输入命令 **npm run serve**启动前台项目（需要安装node环境，本机测试用的node版本为 v12.22.12）。
7. 启动后台springboot的项目
8. 管理员账号密码 system/123456，生产管理与账号密码 ls/123456，厂长账号密码 lc/123456

更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20230808113030126](http://image.javatip.cn/bysj/20230808113030.png)

![image-20230808095222434](http://image.javatip.cn/bysj/20230808095222.png)

![image-20230808094902322](http://image.javatip.cn/bysj/20230808094910.png)

![image-20230808113012633](http://image.javatip.cn/bysj/20230808113012.png)

![image-20230808113109398](http://image.javatip.cn/bysj/20230808113109.png)
