## 321SpringBoot+vue+人脸识别图书馆预约管理系统

项目地址：http://javatip.cn/store/198.html

图书馆预约管理系统基于SpringBoot+vue进行开发。系统分为管理员和普通用户两种角色，普通用户第一次登录后需要现在右上角个人中心中设置头像，只有设置了头像才能在后面预约的时候进行人脸比对。

管理员：

- 用户管理
- 阅览室管理
- 图书馆里
- 座位管理
- 检举审核
- 信用分扣除

普通用户：

- 阅览室查看
- 图书查看
- 座位预约
- 违规检举
- 预约管理
- 人脸识别签到
- 签退
- 中途暂离

### 二、技术框架

- 后端：SpringBoot
- 前端：vue，elementui

### 三、安装教程

1. 用idea打开项目
2. 在idea中配置jdk环境
3. 配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 在application-dev.yml文件中将数据库账号密码改成自己本地的
6. 在application.yml文件中将redis信息修改成自己本地的，redis默认密码为空（需要启动redis）
7. 在idea中进入前台文件夹library-web。在idea底部打开**Terminal**，然后在输入命令**npm install** 下载依赖。等到进度条走完后输入命令 **npm run dev**启动前台项目（需要安装node环境，本机测试用的node版本为 v12.22.12）。
8. 在idea中启动后台项目。管理员账号密码 system/123456，普通用户账号密码 小李/123456。

更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20230808155543865](http://image.javatip.cn/bysj/20230808155544.png)

![image-20230808155158301](http://image.javatip.cn/bysj/20230808155158.png)

![image-20230808155209832](http://image.javatip.cn/bysj/20230808155209.png)

![image-20230808155220001](http://image.javatip.cn/bysj/20230808155220.png)

![image-20230808155237765](http://image.javatip.cn/bysj/20230808155237.png)

![image-20230808155259347](http://image.javatip.cn/bysj/20230808155259.png)

![image-20230808155316320](http://image.javatip.cn/bysj/20230808155316.png)
