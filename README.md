1. 签到模块
1) 首先登录账户，获取 token(作为信息认证)。
2) 发送post 请求获取当前需要签到的签到id和楼层的蓝牙id。
3) 构造数据，蓝牙 id，设备号，手机设备信息，签到 id，发送 post 请求签到。
