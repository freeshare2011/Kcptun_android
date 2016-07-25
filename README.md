# Kcptun_android
#项目说明
这是一个在安卓平台图形化配置并运行kcptun服务的应用，实现代理功能需要配合ShadowSocks使用。

#预编译安装包
[20160726v0.1 下载](https://github.com/shutup/Kcptun_android/releases/tag/v0.1)

#原理图
![logic](https://github.com/shutup/Kcptun_android/blob/master/logic.png "logic")

#使用场景
* 我在使用kcptun的过程中，发现对于shadowsocks确实可以起到提高速度和稳定性的作用，因此希望可以方便的使用它。不过原作者目前只提供了命令行的程序，不是很方便使用，因此我打算做一个安卓的wrapper来包装一下，方便在安卓系统的使用。
* 按照我的理解，我本来打算安装app到手机上后，然后用手机上的shadowsocks来直接连接，结果测试发现并不可行。不过倒是发现app跑在手机上后，同一局域网的设备都可以通过它监听的服务来代理上网了。同时考虑到我的路由器是mips架构，而我的电脑无法长时间开机运行，因此我考虑找个小东西来运行kcptun的服务，考虑过后，我发现我的电视盒子的是个不错的选择。因此便有了本项目的诞生。

#使用说明
安装应用

* 下载预编译的APK包
* 下载项目代码自行编译

配置应用

* 第一次运行时先进行服务器信息配置，配置信息将会保留
* 以后启动APP时会先检查已有配置，进行连接尝试

#感谢
[KcpTun项目](https://github.com/xtaci/kcptun)

