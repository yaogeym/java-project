## 317SpringBoot+vue社区诊所管理系统

### 一、项目介绍

项目地址：http://javatip.cn/store/194.html

社区诊所管理系统基于SpringBoot+vue进行开发。总共分为管理员，医护和患者三种角色。

管理员：

- 用户管理
- 医护信息查看
- 诊疗预约
- 医嘱管理
- 药品管理
- 药品订单
- 药品进货单
- 病例统计
- 药品销量统计
- 药品销售额统计

医护：

- 医护信息管理
- 诊疗预约
- 医嘱管理
- 药品管理
- 药品订单
- 药品进货单
- 病例统计
- 药品销量统计
- 药品销售额统计

患者：

- 注册

- 医护信息查看
- 诊疗预约
- 医嘱查看
- 药品查看
- 个人病例统计

### 二、技术框架

- 后端：SpringBoot，Mybatis
- 前端：vue，echarts，bootstrap

### 三、安装教程

1. 用idea打开项目
2. 在idea中配置jdk环境
3. 配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 在application.yml文件中将数据库账号密码改成自己本地的
6. 在application.yml文件中将redis信息修改成自己本地的，redis默认密码为空（需要启动redis）
7. 在idea中进入前台文件夹clinic-ui。在idea底部打开**Terminal**，使用命令**cd clinic-ui**，然后在输入命令**npm install** 下载依赖。等到进度条走完后输入命令 **npm run dev**启动前台项目（需要安装node环境，本机测试用的node版本为 v12.22.12）。
8. 在idea中启动后台项目。管理员账号密码 system/123456，医生账号密码 doctor/123456，患者账号密码 lm/123456。

更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20230804234118903](http://image.javatip.cn/bysj/20230804234119.png)

![image-20230804234034088](http://image.javatip.cn/bysj/20230804234034.png)

![image-20230804234047568](http://image.javatip.cn/bysj/20230804234047.png)

![image-20230804234144270](http://image.javatip.cn/bysj/20230804234144.png)

![image-20230804234202613](http://image.javatip.cn/bysj/20230804234202.png)
