# 京东萌宠助手

## 功能列表

- [x] 初始化京东宠物信息

- [x] 每日签到

- [X] 三餐签到

  三餐签到每天分为三个时段, 且不能在非三餐时段完成, 所以功能不太完善, 我自己暂时使用crontab实现的

- [x] 投食

- [x] 收取好感度

- [x] 浏览指定店铺

- [x] 浏览店铺集合
  
- [x] 遛弯

- [x] 领取遛弯奖励

- [x] 获取任务完成状态

- [x] 帮好友助力

	默认不开启助力任务
	__需要拿到shareCode, 自己的shareCode现在会在脚本运行时在控制台输出, 可以将其分享给其他人, 
	拿到别人的shareCode后可以找到代码中调用`slaveHelp()`方法的地方, 将注释打开, 并修改slaveHelp()方法中shareCode的值

- [ ] 好友助力我
