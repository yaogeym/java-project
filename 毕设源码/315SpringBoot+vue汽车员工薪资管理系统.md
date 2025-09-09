## 315SpringBoot+vue汽车员工薪资管理系统

### 一、项目介绍

项目地址：http://javatip.cn/store/192.html

汽车员工薪资管理系统基于SpringBoot+vue进行开发，系统分为管理员，人事和员工三种角色，员工工资具体计算方式为

1. 基础工资 = 职称倍率+最低底薪
2. 考勤扣款，缺勤小于3天，工资正常发放，大于等于3天小于7天工资发一半，大于等于7天发一半并提示建议辞退。（员工一天需要打开四次，分别是早上8点前，中午12点到14点之间，下午6点以后，其他时间无法打卡，默认为缺卡状态）
3. 绩效工资：汽车售价 * 销量 * 抽成比例
4. 社保缴纳扣款
5. 个税缴纳扣款

由以上五种方式结合最后计算除工资。

管理员功能：

- 用户管理
- 部门管理
- 汽车信息管理

人事：

- 汽车销量审核
- 个税申报
- 社保缴纳
- 职称系数查看
- 薪资核算

员工：

- 汽车销量上报
- 员工考勤

### 二、技术框架

- 后端：SpringBoot，Mybatis
- 前端：vue，elementui

### 三、安装教程

1. 解压目录后，前台项目在carsalary-ui目录中，idea打开carsalary-ui目录，后台项目在carsalary-system目录中，新开一个idea窗口打开carsalary-system目录
2. 在后台idea中配置jdk环境
3. 在后台配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 在application.yml文件中将数据库账号密码改成自己本地的
6. 在idea中进入前台文件夹carsalary-ui。在idea底部打开**Terminal**，然后分别输入命令**npm install** 下载依赖。等到进度条走完后在**Terminal**中分别输入命令 **npm run serve**启动前台项目（需要安装node环境，本机测试用的node版本为 v12.22.12）。
7. 启动后台springboot的项目
8. 管理员账号密码 system/123456，人事账号密码 hr/123456，普通员工账号密码 ls/123456

更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20230804144912939](http://image.javatip.cn/bysj/20230804144913.png)

![image-20230804144832640](http://image.javatip.cn/bysj/20230804144832.png)

![image-20230804144847172](http://image.javatip.cn/bysj/20230804144847.png)

![image-20230804145017297](http://image.javatip.cn/bysj/20230804145017.png)

![image-20230804145029177](http://image.javatip.cn/bysj/20230804145029.png)

![image-20230804145100120](http://image.javatip.cn/bysj/20230804145100.png)
