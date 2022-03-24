免费的 macOS 菜单栏工具，轻松隐藏图标：Hidden Bar
#################################################

 | Hidden Bar lets you hide menu bar items to give your Mac a cleaner look.
 | Hidden Bar 帮您隐藏菜单栏图标，让您的 Mac 更清爽哟！ *Tony Chang 倾情翻译*

每天使用 Mac 的你，一定安装了不少 App，随着 App 数量的增加，macOS 系统的菜单栏想必也被各种图标占领，你可能也想过，有没有一种小工具，把不常用的图标隐藏起来，看起来清清爽爽。

看看 `Julien Grand-Poisson(@bfishadow)`_ 怎么说：

 | 一直不喜欢乱七八糟的 Menu 图标，之前都在用 Bartender 来管理。但升级 macOS Catalina 之后，它找我索取「全屏录制」权限，于是删了……
 | 今天，发现了一个超级好用的替代品 |:point_right:| `Hidden Bar`_
 | --- `Julien Grand-Poisson(@bfishadow)`_

.. _Julien Grand-Poisson(@bfishadow): https://twitter.com/bfishadow/status/1210578945302659073

.. _Hidden Bar: https://github.com/dwarvesf/hidden

Hidden Bar 非常轻量，简洁的界面和方便的操作实现了隐藏菜单栏图标的需求。

运行 Hidden Bar，菜单栏上会出现一条分割线 :guilabel:`|` 和一个尖括号 :guilabel:`>` 。分割线 :guilabel:`|` 左侧是被隐藏的图标，简称为「隐藏区」，分割线 :guilabel:`|` 右侧则是长期显示的图标，简称为「显示区」。点按尖括号 :guilabel:`>` 用来控制「隐藏区」展开与否。

现在，就可以按住键盘上的 :guilabel:`⌘ command` 键，按自己的喜好拖拽图标了，要隐藏的图就把它拖到分割线 :guilabel:`|` 左侧哦！

要提醒各位，这个小工具有一项「自动隐藏图标」的功能，默认是开启状态，默认时间是 10 秒。所以，为了方便操作，可以先右键单击分割线 :guilabel:`|` > :guilabel:`偏好设置` ，进入设置窗口，把这项功能关闭先。图标都拖动完毕了，再开启。

全局快捷键请自行设置。这里给出我的快捷键仅供参考： :guilabel:`⌘ command` + :guilabel:`⌥ option` + :guilabel:`L` 。

那么，这么好用的 App 要怎么安装呢？

   1. `Mac App Store`_

   2. 下载 ``.dmg`` 包手动安装： `dwarvesf/hidden Releases`_

   3. ``brew`` 安装方式：

      .. prompt:: bash $

         brew cask install hiddenbar

.. _Mac App Store: https://apps.apple.com/cn/app/hidden-bar/id1452453066?mt=12

.. _dwarvesf/hidden Releases: https://github.com/dwarvesf/hidden/releases

