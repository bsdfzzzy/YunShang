# YunShang 项目作业
##项目内容
实现一个后台管理页面，管理人员信息（用户、管理员）和图片信息，基本操作包括查询人员/图片、添加人员/图片、更改人员/图片信息、删除人员/图片

##项目阶段
* 前端：
	- 完成页面编辑，实现基本的后台管理页面，UI尽量美观，可以使用UI框架或者前端模板，在评审时会根据模板或框架中使用到的技术点提问审核
	- 实现登录注册，具体参照后台要求
	- 实现前后端交互，初始化数据可以采用后端渲染，此时要求掌握并运用ajax和DOM的操作
	- 实现图片上传和预览，原生JS

  PS：以上JavaScript要求尽量原生，如果JQuery用得很熟可以使用，暂时不建议。项目过程请根据以上步骤一步步来，会按照步骤和学习情况进行审评。
  
* 后端：
	- 第一阶段
		+ 使用mysql数据库，能验证管理员登录，统一账户名为：beego，密码为： golang，利用session而不是cookie完成
		+ 能添加人员的文本信息，包括：姓名 学号 班级
		+ 对人员信息有以下操作：
			+ 增加人员的操作
			+ 查：作出已有成员的列表，并有相应的”改“”删“的操作
	- 第二阶段 
		+ 能上传人员的图片和图片的相关信息
	    + 图片添加时有相应的”名称“ ”分类“  ”简介“
	    + 图片保存的路径为 /”分类“/”名称“
	    + 对图片的简介有曾删改查的操作 
	- 第三阶段
		+ 图片的预览，具体参照前端

##学习资料
* 前端：
	- 学习[HTML入门](http://www.runoob.com/html/html-tutorial.html)和[HTML5](http://www.runoob.com/html/html5-intro.html)中的input类型、表单和语义元素
	- 学习[CSS](http://www.runoob.com/css/css-tutorial.html)和[CSS3](http://www.runoob.com/css3/css3-tutorial.html)
	- 学习[Bootstrap UI框架](http://www.runoob.com/bootstrap/bootstrap-tutorial.html)
	- 学习[JavaScript](http://www.runoob.com/js/js-tutorial.html)和[DOM](http://www.runoob.com/htmldom/htmldom-tutorial.html)
	- 以上为此次项目作业需要掌握的内容，bootstrap可以不掌握，不过不能保证如果同学们改模板的话不会遇到自己想要的模板是使用了bootstrap的。前端内容较多，现在多为记背性的内容，因此希望大家周末就开始看以上文档，html和css可以在一天内解决然后自己写个小页面尝试一下，html5和css3在这基础上会有增加的属性自己多体悟一下，JS和DOM也希望能在一到一天半内看完。在看文档的时候第一遍看不懂的先过，等全部看完再回来看。第一遍求整体性，回过头来整理细节。

* 后端：
	- go语言学习资料:[Go web 编程 作者：Asta](https://github.com/astaxie/build-web-application-with-golang/tree/master/zh)
	- beego框架学习:[Go web 基础 作者：无闻](http://study.163.com/course/courseMain.htm?courseId=328001)以及官网文档。无闻的视频讲解非常细致，对于上手框架很有帮助，但最根本的还是官方文档，90%beego框架需要查询的资料都可以在beego.me找到
	- 编辑器推荐Atom，[镜像下载源](http://npm.taobao.org/mirrors/atom/)，下载后安装go-plus插件更好用
	- MySQL数据库和git请自行下载，翻墙有问题可以找镜像资源下载。
	- 大家最好按照阶段来制定自己的目标，go语言基础要快速通看，beego框架先分析官方入门文档，之后不断调整自己的代码完成各阶段任务。
