!> 更多关于`PAC 用户自定规则`请 [参考教程](https://www.jianshu.com/p/c68b6fb7ccd7)

## PAC 用户自定规则

* 如PAC模式可上`Google Youtube Facebook`等常用网站，但不能上`xxx`网站，请添加自定规则

* 例如打不开`xxx.com`网站，应在自定规则里添加两行`||xxx.com`和`||www.xxx.com`然后`确定`

![mac](media/mac/rule.gif ':size=480')

!> Windows 同样适用，打开win文件夹，编辑`user-rule.txt`，添加同样的规则即可！[参考规则](https://fuyiyi.imdo.co/articles/2018/09/30/1538314978887.html)

## iPhone/iPad 修改 DNS

* 打开`Potatso Lite`的设置界面-->点击`自定义DNS`-->添加DNS`8.8.8.8`

![apple](media/apple/dns.gif ':size=480')


## QQ、微信等软件代理

* 打开QQ、微信的登陆设置界面，设置`SOCK5代理`地址`127.0.0.1`端口`1080`

![windows](media/win/sock5.gif ':size=480')

!> 其他软件只要支持`SOCK5`代理设置，都可通过以上方法实现代理功能，Linux/MacOS 同样适用！

!> 手机App实现的是网络层的代理，不再需要单独设置`SOCK5`代理，只要设置好`路由模式`就可以！
