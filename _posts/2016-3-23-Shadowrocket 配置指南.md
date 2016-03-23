---
layout: post
title: "Shadowrocket "
date: "2016-03-23 12:08:51 +0800"
categories: gfw
published: true
---



### 写在前面    
首先你需要一个Shadowsocks账号，这个软件基本上是一个本地代理（类似Surge），通过事先写好的规则‘自动’判断网络流量走向（shadowsocks加密通道（爬墙通道），服务加速通道（apple），直接连接）

### 开始
1. 下载App [点我](https://itunes.apple.com/us/app/shadowrocket-for-shadowsocks/id932747118?mt=8#) （这是美国区的，中国区已下架）
2. 打开app，进入主界面，我们一共要配置2个地方，一个是shadowsocks服务器配置，一个是Surge规则配置。我们首先点击Setting，进入Surge规则设置界面。  ![1]({{site.baseurl}}/_src/20160323_shadowrocket/1.jpg)
3. 点击Surge，进入Surge配置界面，![2]({{site.baseurl}}/_src/20160323_shadowrocket/2.jpg)  然后点击右上的+号![log]({{site.baseurl}}/_src/20160323_shadowrocket/7.PNG)  输入配置文件地址*http://fuckgfw.com/main.conf*<b style="color: red">（这里要替换成你自己的配置文件地址）</b>，输完后点击Download。![url]({{site.baseurl}}/_src/20160323_shadowrocket/8.PNG)  
4. 接下来在REMOTE CONFIG这一栏就出现了你刚才输入的配置文件地址，点击地址，选择Use Config。![3]({{site.baseurl}}/_src/20160323_shadowrocket/3.jpg)  
5. 我们需要确认一些配置文件是否正确加载了，点击Modify Config...，确认是否是你的配置文件。![verify]({{site.baseurl}}/_src/20160323_shadowrocket/4.jpg)  
6. 回到上一界面，进入Proxy设置，把logging打开。![log]({{site.baseurl}}/_src/20160323_shadowrocket/5.jpg)  
7. 这样Surge规则配置就OK了，下面我们来设置Shadowsocks，回到主界面，点击右上角+号进入Shadowsocks配置界面![6]({{site.baseurl}}/_src/20160323_shadowrocket/6.jpg),按下图填入服务器信息
8. 接下来打开VPN开关，尽情享受自由的互联网吧。
