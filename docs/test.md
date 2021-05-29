
!> 连通性测试成功，说明该节点的服务器没问题。应从系统代理设置查找问题！

## iPhone/iPad

* 打开小火箭-->选择节点-->点击`连通性测试`：显示`xxx ms`说明成功；显示`超时`则节点不可用！

![test](media/apple/test.gif ':size=480')

## Android 系统

* 打开小飞机-->选择节点-->点击底部的`测试连接`：显示HTTPS握手延迟`xxx 毫秒`说明连接成功！

![test](media/android/test.gif ':size=480')

## Windows 系统

* 点击下载 <a href="media/win/tcping.exe" target="_blank">tcping.exe</a> 复制到`C:\Windows\System32`打开`命令提示符`输入`tcping 服务器地址 端口`

![test](media/win/test.gif ':size=640')

## Linux/MacOS 

* 打开`终端`输入`nc -vz -w1 服务器地址 端口`连测三次，结果都显示`succeeded!`说明成功！

![test](media/linux/test.gif ':size=640')

!> 如测试失败，请查看`账号是否过期 超流量`并核对`服务器地址 端口 密码 加密方式`后再测试

!> 排除服务器问题后，应从系统代理设置找问题，系统代理设置可能被某些软件或插件锁死

!> 如360、电脑管家、毒霸等国产安全类软件，一些浏览器插件也会锁住浏览器的代理设置
