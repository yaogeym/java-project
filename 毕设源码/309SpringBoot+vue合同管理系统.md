## 309SpringBoot+vue合同管理系统

### 一、项目介绍

项目地址：http://javatip.cn/store/187.html

合同管理系统基于SpringBoot+vue进行开发，用户添加合同信息，管理员进行审核。

管理员功能：

- 用户管理
- 部门管理
- 合同管理
- 合同审核

- 时长统计
- 签定量统计

员工功能：

- 新增合同
- 导出合同
- 附件下载

### 二、技术框架

- 后端：SpringBoot，Mybatis
- 前端：vue，elementui

### 三、安装教程

1. 解压目录后，前台项目在contract-ui目录中，idea打开contract-ui目录，后台项目在contract-system目录中，新开一个idea窗口打开contract-system目录
2. 在后台idea中配置jdk环境
3. 在后台配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 在application.yml文件中将数据库账号密码改成自己本地的
6. 在idea中进入前台文件夹contract-ui。在idea底部打开**Terminal**，然后分别输入命令**npm install** 下载依赖。等到进度条走完后在**Terminal**中分别输入命令 **npm run serve**启动前台项目（需要安装node环境，本机测试用的node版本为 v12.22.12）。
7. 启动后台springboot的项目
8. 管理员账号密码 system/123456，员工账号密码：xw/123456

更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20230803141656243](http://image.javatip.cn/bysj/20230803141659.png)

![image-20230803141835100](http://image.javatip.cn/bysj/20230803141835.png)

![image-20230803143535372](http://image.javatip.cn/bysj/20230803143535.png)

![image-20230803143626687](http://image.javatip.cn/bysj/20230803143626.png)
