## 322SpringBoot+vue问卷调查系统

项目地址：http://javatip.cn/store/202.html

问卷调查系统基于SpringBoot+vue进行开发。系统分为管理员和普通用户两种角色，管理员主要是用来添加问卷，普通用户主要填写问卷。

管理员：

- 问卷查看
- 问卷删除
- 新增问卷
- 添加问题
- 删除问卷
- 发放问卷
- 结束问卷
- 用户管理

- 图表统计

普通用户：

- 注册登录
- 填写问卷

### 二、技术框架

- 后端：SpringBoot，Mybatis
- 前端：vue，elementui

### 三、安装教程

1. 解压目录后，前台项目在questionnaire-web目录中，idea打开questionnaire-web目录，后台项目在questionnaire目录中，新开一个idea窗口打开questionnaire目录
2. 在后台idea中配置jdk环境
3. 在后台配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 在application.yml文件中将数据库账号密码改成自己本地的
6. 在idea中进入前台文件夹questionnaire-web。在idea底部打开**Terminal**，然后分别输入命令**npm install** 下载依赖。等到进度条走完后在**Terminal**中分别输入命令 **npm run serve**启动前台项目（需要安装node环境，本机测试用的node版本为 v12.22.12）。
7. 启动后台springboot的项目
8. 浏览器输入 http://localhost:8080 进行访问
9. 管理员账号密码 admin/123456，普通用户账号密码 李明/123456

更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20230809100656646](http://image.javatip.cn/bysj/20230809100656.png)

![image-20230809100056883](http://image.javatip.cn/bysj/20230809100113.png)

![image-20230809100445989](http://image.javatip.cn/bysj/20230809100446.png)

![image-20230809100501106](http://image.javatip.cn/bysj/20230809100501.png)![image-20230809100630295](http://image.javatip.cn/bysj/20230809100630.png)

