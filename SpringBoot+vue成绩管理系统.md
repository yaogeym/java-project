## 150SpringBoot+vue成绩管理系统

### 一、项目介绍

项目地址：http://javatip.cn/store/266.html

成绩管理系统基于SpringBoot+vue进行开发，系统总共分为管理员，班主任，老师和学生四种角色，下面是四种角色的详细功能。

管理员：

- 班主任管理
- 教师管理
- 学生管理
- 年级管理
- 班级管理
- 课程管理
- 给教师添加课程
- 给班主任绑定班级
- 考试管理
- 查看成绩

班主任：

- 学生管理
- 查看考试
- 查看成绩

教师：

- 录入成绩

学生：

- 个人成绩查看

- 个人信息查看

### 二、技术框架

- 后端：SpringBoot，Mybatis
- 前端：vue，elementui，echarts，

### 三、安装教程

1. 用idea打开后台项目
2. 在idea中配置jdk环境
3. 配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 在application.yml文件中将数据库账号密码改成自己本地的
6. 在idea中进入前台项目。在idea底部打开**Terminal**，然后在输入命令**npm install** 下载依赖。等到进度条走完后输入命令 **npm run serve**启动前台项目（需要安装node环境，本机测试用的node版本为 v16.20.2）。
7. 在idea中启动后台项目。管理员账号密码 admin/123456，其他角色可在管理员登录后查看，密码都是123456，新建用户默认密码也是123456。

更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20231209141535649](http://image.javatip.cn/bysj/20231209141536.png)

![image-20231209115804835](http://image.javatip.cn/bysj/20231209115805.png)

![image-20231209140314654](http://image.javatip.cn/bysj/20231209140314.png)

![image-20231209140352808](http://image.javatip.cn/bysj/20231209140352.png)

![image-20231209140935712](http://image.javatip.cn/bysj/20231209140935.png)
