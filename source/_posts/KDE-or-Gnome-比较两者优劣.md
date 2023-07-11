---
title: KDE or Gnome? 比较两者优劣
date: 2023-02-05 15:20:57
tags: Linux 
---
# 个人使用背景

KDE和Gnome我都用过，本人从2021年开始接触Linux，用的是Ubuntu，桌面环境也默认是Gnome，直到上个月，Gnome是在用不下去了，在众多网友的推荐之下，我开始用KDE。结果是，我用了几天，马上删了Gnome，一个字，爽！

# 为什么选择Gnome？

## 发行版

Gnome是大多数主流发行版的默认桌面，包括Ubuntu，Debian，Fedora...，所以很多用户第一次安装Linux，就是用Gnome

## 体验

Gnome有着极好的开箱使用体验，各种软件一应俱全，甚至快捷键都配置好了，默认主题的视觉感受也不错，而KDE则需要你自己去配置一堆东西，才能达到赏心悦目的效果，这一点，KDE已经劝退了一部分用户了。

![gnomedesktop](Gnomedesktop.png)

![gnomeapps](Gnomeapps.png)

## 风格

Gnome最大的特点就是简约。设置里面可以自定义的选项不多，顶栏也很简单，中间显示时间，旁边显示基本状态，如果需要更多的自定义，可以安装Tweaks和相关主题。

    sudo apt instll gnome-tweaks

![gnometweaks](Gnometweaks.png)

## 资源占用

Gnome开机1G内存，KDE开机2G，你说呢

![gnomesys](Gnomesys.png)

# 为什么选择KDE？

## 自定义

Gnome可以自定义的地方很有限，但是在KDE里面，你可以改所有你想改的内容，并且是原生支持--不用担心兼容性，包括桌面插件，状态栏小组件，设置等等；而Gnome需要自行安装插件，并且一次大版本更新一堆插件就挂掉

![KDE桌面](KDEdesktop.png)

## 移动设备交互

KDE自带KDE Connect，虽然现在Gnome也有了，但是功能还没有那么完善
![KDEconnect](KDEconnect.png)
## 兼容性

不知道为什么，可能是KDE基于Qt，很多软件（QQ音乐，钉钉）在Gnome下运行会出现很多问题，QQ音乐没声音，缩放问题，无法输入中文......在KDE下居然一切正常！

奇怪的知识又增加了

## 功能

很多同类软件，KDE比Gnome的功能多很多，UI设计也好一些；添加桌面快捷方式，KDE可以像Windows一样直接拖动，甚至还可以选择图标；而Gnome的桌面快捷方式很不稳定，容易挂掉，并且对权限有特殊要求，新建一个要自己手敲.desktop文件

![KDEicon](KDEicon.png)

# 总结

如果不想折腾，或者配置不行的，Gnome；
如果追求个性化的，有技术基础的，KDE