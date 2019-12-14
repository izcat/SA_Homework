
# Software Architect Homework
软件体系结构大作业 ——仓库管理系统
=======
本项目为西电大三软件体系结构大作业，需要搭建一个功能简单的工具仓库，具体需求可见“软件体系结构课程大作业-工具仓库.doc”。

由于项目需求量较小，且大作业完成时间比较仓促，因此部分功能暂时没有实现，代码架构也不是很完美，敬请谅解。

本次大作业采用HTML+CSS+JS作为前端，后端采用Flask框架进行搭建，数据库采用MySQL构建。由于队伍中没有对前端很熟悉的，因此采用Flask中的jinjia2模板作为前端的渲染模板，而为进行前后端分离的工作

项目中web.py为后端代码，其中包含了与数据库的所有操作，templates和static文件中分别放置了经过jinjia2渲染后的html和js文件，其余.py文件则是需求文件第二问中模拟管理员接受工具请求，机器人将工具运送到传送带，传送到传送工具到出口的过程。create_database.sql为数据库的建表操作。在部署时，可能需要在web.py中修改数据库的相关参数，包括用户名密码等，并且需要手动添加部分数据到数据库中。 

源码编写工作与github.com/frozenlalala 一同完成，该项目为其拷贝。
可参考https://github.com/frozenlalala/software_homework
