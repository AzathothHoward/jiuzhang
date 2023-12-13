# 九章云台

# 定时任务调度库

quartz调度库



# 血缘关系整理

antlr4

 

# 图数据库

Neo4J



# 前后端登录交互

json web token

前端填写用户名和密码，后端计算一个json web token放回前端。前端存储json web token存储在cookies中，有个过期时间

第一次登录后，每一次的前端向后端发送请求，都会带上tokne访问后端，后端就知道了是哪个用户，就不需要再登录了，不会重定向登录界面

json web token有一个鉴权的功能
M
后端也可以通过这个json web token来判断当前用户的权限