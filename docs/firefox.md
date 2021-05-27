
!> 请先安装 [Firefox 浏览器](https://www.mozilla.org/zh-CN/firefox/) 本教程解决 Win/Mac/Linux 客户端正常，但系统代理被"锁死"的问题

## SwitchyOmega

* 点击安装 [SwitchyOmega 插件](https://addons.mozilla.org/zh-CN/firefox/addon/switchyomega/)。打开浏览器设置-->扩展和主题-->Proxy SwitchyOmega-->首选项

![linux1](media/firefox/1.gif ':size=720')

* ① 选择“proxy”情景模式 --> ② 设置代理服务器：`SOCKS5` `127.0.0.1` `1080` --> ③ 应用选项

![linux2](media/firefox/2.gif ':size=720')

* 需要用代理时，请选`"proxy"`模式，日常请使用`"系统代理"`模式。更多设置和Chrome教程请[参考文档](https://github.com/FelisCatus/SwitchyOmega/wiki)

![linux3](media/firefox/3.gif ':size=720')

!> 常见问题

  ```shell
按教程设置后连接不能用！
```
Firefox 插件不能独立的使用，`必须`配合电脑端的客户端才能工作！

  ```shell
上国内网站卡，流量消耗快！
```
本教程实现的是Firefox全局代理，不需代理时请换`系统代理`模式

  ```shell
Firefox 能科学上网，其他浏览器不行！
```
本教程实现的是Firefox全局代理，其他浏览器默认使用"系统代理"

  ```shell
如何离线安装 SwitchyOmega 插件
```

Firefox 插件：<a href="media/firefox/switchyomega.xpi" target="_blank">SwitchyOmega</a>

Chrome 插件：<a href="media/firefox/switchyomega.crx" target="_blank">SwitchyOmega</a>

如何安装？百度搜索关键字`离线安装SwitchyOmega`
