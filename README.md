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