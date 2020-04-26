---
layout:     post   				    # 使用的布局（不需要改）
title:      基于PicGo的GitHub图床		# 标题 
subtitle:   Blog功能日趋完善中...		# 副标题
date:       2020-04-26 				# 时间
author:     yujinghao007 			# 作者
header-img: img/home-bg.jpg 		# 这篇文章标题背景图片
catalog: true 						# 是否归档
tags:								# 标签
    - blog
---

# 前言
&emsp;&emsp;之前写的三篇blog都不太用图片，但其实我在原来的wordpress博客里写的基本都配了图，说到底还是因为wordpress的编辑器方便吧。于是想着自己搭一个在线图床，markdown也能用图片咯。
# 寻找
&emsp;&emsp;首先我百度了一通，在茫茫多的Lychee图床里看到了[一篇PicGo的教程](http://www.eryajf.net/3022.html)，也算运气好。Lychee图床虽然可以，本地搭建+nginx前端的结构使得它的灾备能力不够，况且我的blog也是建立在GitHub上的云端备份，用PicGo在GitHub上再建一个在线图床岂不是正好。
# 动手
&emsp;&emsp;有了教程一切都好办，以下是步骤：  


1. 先到[PicGo](https://github.com/Molunerfinn/PicGo)的GitHub页面里下载最新的release
2. 在GitHub的仓库里建好PicGo的repo
3. 在GitHub的[个人页面](https://github.com/settings/tokens)里创建token
4. 配置PicGo ![配置PicGo](https://raw.githubusercontent.com/WilliamStark9527/PicGo/master/img/批注 2020-04-26 213336.jpg)
5. give it a try
# 总结
&emsp;&emsp;其实也没啥难的。

&emsp;&emsp;GitHub牛啤。