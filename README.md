# community
	community for study
	本项目偏后端练习运用。

## 作品功能用途 ##：
**用户模块**：具有邮箱注册，登录，修改密码，上传头像，添加和修改个人资料等功能。<br>
**帖子模块**：在相关技术模块内可以发布帖子，排版可以供用户选择。用户可以选择帖子进行回复信息。<br>
**帖子搜索**：用户可以根据关键字，模块分类等信息进行搜索相关帖子，缩小筛选范围。<br>
**技术分类板块**：根据不同的技术类型进行分类，将帖子划分。<br>
**新用户版块**：可以看到最近一个月内新注册的用户。<br>
**近一个月帖子版块**：可以快捷查看金一个月的帖子。<br>
**消息提示功能**：自己帖子得到别人回复后有数字显示。<br>

## 技术特点 ##：
①由maven构建的多模块项目，各个子项目可以统一的进行管理，也可以有各自的特色（按需引入jar包）<br>
②后端采用主流的ssm（Spring+SpringMVC+MyBatis）框架，spring作为控制反转（ioc）和面向切面（aop）的容器框架，Spring MVC主要由DispatcherServlet、处理器映射、处理器(控制器)、视图解析器、视图组成。MyBatis则作为数据库的持久层框架<br>
③Restful风格接口，包含资源的定义、获取、表述、关联、状态变迁等<br>
④Redis缓存技术，key-value存储系统，值（value）可以是 字符串(String), 哈希(Map), 列表(list), 集合(sets) 和 有序集合(sorted sets)等类型<br>
⑤Log4j日志系统，控制日志信息输送的目的地是控制台、文件、GUI组件，控制每天日志的输出格式<br>
⑥严谨的编码规范，低耦合高维护性，统一的接口回复格式以及接口异常回复格式<br>
⑦Thymeleaf独立的java服务端模板引擎。能够处理html，xml，javas，css等<br>
⑧layui自身模块规范编写的前端 UI 框架，遵循原生 HTML/CSS/JS 的书写与组织形式,前端采用社区模板<br>
⑨tomcat主流java的web应用服务器<br>


