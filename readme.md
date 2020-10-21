# 颜色控制

	1. 添加新的颜色blue, green, yellow, red
	2. 使用curTileColor全局变量来控制当前格子的颜色
	3. 通过随机数生成器来产生随机的颜色
	4. 修改了newtile和settile

# 形状

	1. 目前需要修改的函数

		

	2. 需要添加新的形状及旋转方向
		- 利用数组指针p_allRotations_shap存储几种不同的形状以及不同的方向
		- 利用指针currentRotationShape来指向目前的形状
		- 利用随机数生成器来产生0至6的均匀随机数以便在newtile时产生不同的形状
		- 注意，使用到当前形状的的有newtile函数和rotate函数
	3. 对于碰撞的实现，主要是修改checkvalid函数，增加了查看当前的格子是否被填满

# 图形验证
# 数据库分管用户
	- 用户列表
		- ID表
	- 密码表
# 随机密码生成器
	- 数据库加密
	- 本地缓存
# 保存密码