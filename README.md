# 中文简体 | [English](https://github.com/DHDAXCW/NanoPi-R2S-2021/blob/main/EngLish.md)
# NanoPi-R2S-2021 每天自动更新插件和内核版本。
## ``` 由于源码无法从硬盘拿出来，只好重新做了。，目前重构进度只有70%用在本镜像闭源上，后期尽量处理，这一个月已更新了下面这几点东西 ```
## 强烈推荐三星TF卡\海康TF卡。哪怕是很难刷上的固件，只有三星刷上可以开机。
### 注：不要用恢复备份。。不保证某个插件是否正常运行。。。建议重新设置贼好！！！
这一个月我没电脑都在讨乞（求电脑中~）。。。
### 默认编译

- 用户名：root 密码：password 管理IP：192.168.2.1

- 下载地址,目前已分stable稳定版和beta测试版,注意区分(感谢xenstar的提议)： https://github.com/DHDAXCW/NanoPi-R2S-2021/releases
- 精简版  ： https://github.com/DHDAXCW/NanoPi-R2S-R4S-2021-mini/releases
- 电报群：https://t.me/DHDAXCW
- TG频道：https://t.me/FWR2SR4S
# 赏个鸡腿吧
 ![Alt text](data/2.jpg?raw=true "Title")
### 如果你觉得此项目对你有帮助，可以捐助我们，以鼓励项目能持续发展，更加完善
# 插件展示
 ![Alt text](data/20.jpg?raw=true "Title")
## 提示
 - 我的固件加了动态超频，不管热不热这是取决后台运行程序在跑什么。
 - 感觉很热  就加风扇，推荐 风扇6cm×6cm，薄1cm，usb也行 或者端子线zh1.5
 - 更新模块有很严重的问题 目前开发者无法修复

### 版本日志 5.6
- 新增虚拟内存
- 修复缺失依赖导致编译安装失败
- 解决NTA Type测试为FullCone
- 新增阿里ddns
- 解决后台进不去
- 优化 提高系统的稳定性
- 优化 提高后台运行快
- 完美解决passwall瞎问题
- 回归多拔，负载均衡
- 新增多个网卡驱动
- 内核版本更新5.4.115
- 尝试移除超频，改为官方默认频率
- 尝试移除某个插件内核模块，防止带上内核一块儿崩溃
- 优化 提高系统的稳定性
- 优化 提高后台运行快
