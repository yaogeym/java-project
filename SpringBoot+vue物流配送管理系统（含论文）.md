## 323SpringBoot+vue物流配送管理系统（含论文）

### 一、项目介绍

项目地址：http://javatip.cn/store/203.html

物流配送管理系统基于SpringBoot+vue进行开发。总共分为管理员和配送人员两种角色。

管理员：

- 用户管理
- 商品管理
- 配送清单管理
- 路线规划
- 配送导航
- 历史清单
- 清单统计

配送人员：

- 清单配送
- 清单完成
- 备忘录
- 休息提醒

### 二、技术框架

- 后端：SpringBoot，Mybatis
- 前端：vue，bootstrap

### 三、安装教程

1. 用idea打开项目
2. 在idea中配置jdk环境
3. 配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 在application.yml文件中将数据库账号密码改成自己本地的
6. 在application.yml文件中将redis信息修改成自己本地的，redis默认密码为空（需要启动redis）
7. 在idea中进入前台文件夹wuliu-ui。在idea底部打开**Terminal**，使用命令**cd clinic-ui**，然后在输入命令**npm install** 下载依赖。等到进度条走完后输入命令 **npm run dev**启动前台项目（需要安装node环境，本机测试用的node版本为 v12.22.12）。
8. 在idea中启动后台项目。管理员账号密码 system/123456，配送人员账号密码 wang/123456

更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20230809115245436](http://image.javatip.cn/bysj/20230809115246.png)

![image-20230809115122638](http://image.javatip.cn/bysj/20230809115122.png)

![image-20230809115104860](http://image.javatip.cn/bysj/20230809115105.png)

![image-20230809115139691](http://image.javatip.cn/bysj/20230809115139.png)

![image-20230809115149508](http://image.javatip.cn/bysj/20230809115149.png)

![image-20230809115201554](http://image.javatip.cn/bysj/20230809115201.png)

![image-20230809115227714](http://image.javatip.cn/bysj/20230809115227.png)
