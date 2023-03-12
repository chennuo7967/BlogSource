---
title: 自制Ubuntu
date: 2023-03-11 22:15:44
tags: "Linux"
---

# Why修改？
首先，个人觉得Ubuntu默认的Gnome不好用，而且难看，所以换了KDE。具体可以参见我以前的[文章](https://chennuo7967.github.io/2023/02/05/KDE-or-Gnome-%E6%AF%94%E8%BE%83%E4%B8%A4%E8%80%85%E4%BC%98%E5%8A%A3/)

然后，每次安装Ubuntu都要重新装一堆东西，换源，设置，美化......实在麻烦

最后，我在市面上找不到一个对于我而言可以开箱即用的发行版，于是我决定

**自己动手，丰衣足食！**

*******
# 修改说明
## 关于外观        
1，图标主题默认 [Papirus Dark](https://github.com/PapirusDevelopmentTeam/papirus-icon-theme/)
2，Plasma样式默认 [Future Dark](https://store.kde.org/p/1491485/)
3，窗口装饰元素为 [WhiteSur Dark](https://store.kde.org/p/1398840/)
4，壁纸为默认深色模式壁纸        
5，增加字体 [HarmonyOS Sans](https://communityfile-drcn.op.hicloud.com/FileServer/getFile/cmtyPub/011/111/111/0000000000011111111.20221101115044.33201174322571893280998053929524:50531031060425:2800:6DA5B24196810B0861671524221560A081031A0859326AD524B15C316D0AB6F9.zip?needInitFileName=true)        
6，SDDM主题更改为 [Sugar Candy](https://store.kde.org/p/1312658)

## 关于应用        
1，将Ubuntu的Gnome更换为KDE，并添加相应PPA源
2，将LibreOffice更换为WPS
3，预置Clash，放在了/opt/clash下
4，预置VS Code
5，预置gcc，git，vim
6，将软件源更改为中科大源(如果没有请自行用桌面上的sources.list更换)
7，删除Snap以及附属组件
8，将Firefox更换为Google Chrome
9，预装VLC，删除Rhythmbox

## 关于系统设置        
1，修改.bashrc，美化Bash提示符样式        
2，加入一些常用命令的alias，具体见 ~/.bashrc
3，更换内核为Linux6.1.7(LTS)

## 其他        
这个修改版用Cubic基于Ubuntu22.10制作，为了避免体积臃肿，这个版本没有中文输入法以及其他软件如微信、QQ、钉钉，如有需要请自行安装

**[百度云下载链接](https://pan.baidu.com/s/13R8YSFWEc0rVJca0TqN4RQ?pwd=7967)**

后天区一模，考完有时间会考虑出教程

2023.3.11