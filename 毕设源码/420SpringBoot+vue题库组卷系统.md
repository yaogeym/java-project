## 420SpringBoot+vue题库组卷系统

### 一、项目介绍

项目地址：http://javatip.cn/store/806.html

题库组卷系统是由SpringBoot+vue开发的前后端分离的项目，系统分为管理员和普通用户两种角色。管理员进行图库管理，组卷时自动抽取题库题目达到总分100分，普通用户登录后进行答题交卷，答题过程中可以收藏题目，交卷后自动阅卷，系统含有错题本和习题收藏夹，一遍用户后续熟悉题目。自动阅卷后可以看到成绩及答题详情，管理员可以对提交的试卷进行总结。具体角色及功能如下：

管理员：

- 问题管理
- 组卷管理
- 考试成绩查看
- 查看考试详情
- 添加总结

普通用户：

- 用户注册
- 考试列表
- 答题
- 收藏题目
- 交卷
- 考试详情
- 考试总结
- 收藏夹
- 错题本

### 二、技术框架

- 后端：SpringBoot，jpa
- 前端：vue，Ant

### 三、安装教程

1. 用idea打开项目
2. 在idea中配置jdk环境
3. 配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 在application.yml中将数据库账号密码改成自己本地的
6. 安装nodejs环境
7. 在idea中用新窗口打开前端项目，使用`npm install`命令，本机测试nodejs版本为（v12.22.12）
8. 下载完成后输入启动命令启动前台项目，`npm run serve`
9. 后台启动运行

>访问地址：http://localhost:8000，管理员账号密码：admin/admin123，普通用户账号密码：wm/admin123


更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20240807112359427](http://image.javatip.cn/bysj/20240807112359.png)

![image-20240807112419721](http://image.javatip.cn/bysj/20240807112419.png)

![image-20240807112436886](http://image.javatip.cn/bysj/20240807112436.png)

![image-20240807112305574](http://image.javatip.cn/bysj/20240807112305.png)

![image-20240807112021718](http://image.javatip.cn/bysj/20240807112021.png)

![image-20240807112328276](http://image.javatip.cn/bysj/20240807112328.png)

![image-20240807112345022](http://image.javatip.cn/bysj/20240807112345.png)
