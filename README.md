# cloudreve，部署至railway.app
~~因为abuse, reilwaiy已经屏蔽cloudreve关键字，凡是出现了直接不能部署~~
还是不是很推荐大家使用railway进行部署，动不动就封帐号，风控很离谱，没啥保障

这里推荐几个平台
+ 阿里云函数（推荐）
虽然公网流量费用需要钱，但人不多的话还可以接受，一个月1-2g，也就1元一个月，一年10元左右

+ azure（推荐）
azure提供一个免费的容器，每天有几百m的免费额度，可选香港，速度快
**需要信用卡或学生账号**
全名`azure web应用程序`

+ koyeb
pass平台，提供免费容器，至于封好策略还不是很清楚

+ fly.io
提供每月100g流量免费额度

如有任何问题，欢迎提issue
## 功能特性
+ 每日检查cloudreve更新，并自动更新
+ 本项目基于github action和railway cli

## 快速使用
[阿里云函数](./aliyun.md)
[railway](./railway.md)


## 注意事项
+ 因为本项目每日都会更新部署，所有强烈建议用mysql保证数据持久化