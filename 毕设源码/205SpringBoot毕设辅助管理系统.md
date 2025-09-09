## 205SpringBoot毕设辅助管理系统

### 一、项目介绍

项目地址：http://javatip.cn/store/115.html

毕设辅助管理系统SpringBoot+Mybatis进行开发，实现学生和导师的互选，学生和老师互选，总共四轮选择，需要管理员开启选择轮次，前三轮，学生选择老师，然后老师确认才算选择成功，第四轮开启后，智能由管理员进行分配。一个导师最多能选择8个学生。以下是主要功能：

管理员：

- 学生管理
- 教师管理
- 轮次开启关闭
- 学生分配
- 实习周记管理
- 毕设管理

教师：

- 教师查看
- 实习周记审批
- 毕设审批
- 反选学生

学生：

- 学生查看
- 实习周记填报
- 毕设填报
- 选择导师

### 二、技术框架

- 后端：SpringBoot，Mybatis
- 前端：layui

### 三、安装教程

1. 用idea打开项目
2. 在idea中配置jdk环境
3. 配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 在application.yml文件中将数据库账号密码改成自己本地的
6. 启动运行，浏览器输入 `http://localhost:8080` 即可访问。管理员账号密码 system/123456，教师账号密码 2004/123456，学生账号密码 1001/123456

更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20230718101747520](http://image.javatip.cn/bysj/20230718101755.png)

![image-20230718101822561](http://image.javatip.cn/bysj/20230718101822.png)

![image-20230718101837244](http://image.javatip.cn/bysj/20230718101837.png)

![image-20230718101853707](http://image.javatip.cn/bysj/20230718101853.png)

![image-20230718101959616](http://image.javatip.cn/bysj/20230718101959.png)

![image-20230718102010409](http://image.javatip.cn/bysj/20230718102010.png)

![image-20230718102033949](http://image.javatip.cn/bysj/20230718102034.png)
