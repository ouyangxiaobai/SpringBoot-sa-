# 项目名称

SpringBoot破产企业资产拍卖信息系统设计与实现源码+论文+ppt+开题报告+讲解视频（包安装）

# 系统介绍
资产拍卖系统是根据市场需求的实际情况按照网络化的需求开发的，它的目标非常明确，即通过建立拍卖平台，将原来定时定点线下交易方式转变成通过网络平台进行拍卖的线上模式，使拍卖更加便捷、安全、规范和有针对性。

系统功能需求整体上分为用户使用功能和系统管理功能，其中用户使用功能包括用户浏览拍卖产品、用户登录、用户注册、用户查看常见问题、用户查看新闻资讯、用户查看个人信息等功能；系统管理功能包括管理员管理用户、管理员管理拍卖品、和管理员管理系统设置等功能。

根据需求来分析功能模块，进一步明确所需要完成的功能明细点模块，然后连成一个闭环，每个流程环环相扣，并且排除耦合的情况。在将逻辑需求转换成实际内容根据指定好的模型在进行开发。系统设计不仅仅要需求和功能明确，还要在功能模块的前提上设计好页面的交互，好的页面交互能让数据库设计如鱼得水。系统主要包括前台和后台两部分，后台人员主要负责维护基础处理的初始化，和数据管理功能管理等维护工作，前台人员即是普通用户人员，登录验证成功后即可对应权限操作系统。下面分别对这三个角色的功能进行描述：

用户

他们可以登录，可以注册，查看拍卖项目，

用户主要功能如下（图3-1为用户用例图）：

登录；
注册。
查看拍卖项目
收藏拍卖项目
查看新闻
收藏新闻
拍卖项目留言
查看常见问题
银行卡管理
提现管理
个人信息
修改密码
修改支付密码
报名的项目
领先的项目.

# 环境需要

1.运行环境：最好是java jdk 1.8，我们在这个平台上运行的。其他版本理论上也可以。\
2.IDE环境：IDEA，Eclipse,Myeclipse都可以。推荐IDEA;\
3.tomcat环境：Tomcat 7.x,8.x,9.x版本均可\
4.硬件环境：windows 7/8/10 1G内存以上；或者 Mac OS； \
5.数据库：MySql 5.7版本；\
6.是否Maven项目：否；

# 技术栈

1. 后端：Spring+SpringMVC+Mybatis\
2. 前端：JSP+CSS+JavaScript+jQuery

# 使用说明

1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并导入项目的sql文件；\
2. 使用IDEA/Eclipse/MyEclipse导入项目，Eclipse/MyEclipse导入时，若为maven项目请选择maven;\
若为maven项目，导入成功后请执行maven clean;maven install命令，然后运行；\
3. 将项目中springmvc-servlet.xml配置文件中的数据库配置改为自己的配置;\
4. 运行项目，在浏览器中输入http://localhost:8080/ 登录

# 高清视频演示

https://www.bilibili.com/video/BV1Va411p7mM/

​