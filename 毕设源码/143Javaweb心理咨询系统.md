## 143Javaweb心理咨询系统

### 一、项目介绍

项目地址：http://javatip.cn/store/212.html

心理咨询系统使用原生的java技术开发，通过sevlet+jsp来实现前后端数据交互，通过jdbc进行数据存储。系统分为三种角色，分别是管理员，咨询师和访客。

管理员功能如下：

- 咨询师管理
- 来访者管理
- 问卷管理
- 消息发送
- 收件箱
- 发件箱
- 公告管理
- 留言管理

咨询师功能如下：

- 咨询申请管理
- 咨询记录
- 消息发送
- 收件箱
- 发件箱
- 留言管理
- 公告查看

访客功能如下：

- 注册登录
- 预约咨询师
- 我的预约
- 我的咨询
- 消息发送
- 收件箱
- 发件箱
- 留言管理
- 公告查看

### 二、技术框架

- 后端：jdbc，sevlet
- 前端：jsp

### 三、安装教程

1. 用idea打开项目

2. 在idea中配置jdk环境

3. 配置tomcat8.0

4. 新建数据库，导入数据库文件

5. 在pool.properties文件中将数据库账号密码改成自己本地的

6. 启动运行

    ```java
    管理员访问地址：http://localhost:8080/admin/login.jsp, 账号密码 admin/123456
    咨询师访问地址：http://localhost:8080/doctor/login.jsp，账号密码 18888888888/123456
    访客访问地址：http://localhost:8080/client/login.jsp，账号面膜 18899888899/123456
    ```

更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20230814112357588](http://image.javatip.cn/bysj/20230814112405.png)

![image-20230814113330956](http://image.javatip.cn/bysj/20230814113331.png)

![image-20230814113404861](http://image.javatip.cn/bysj/20230814113405.png)

![image-20230814112952355](http://image.javatip.cn/bysj/20230814112952.png)

![image-20230814113149768](http://image.javatip.cn/bysj/20230814113150.png)
