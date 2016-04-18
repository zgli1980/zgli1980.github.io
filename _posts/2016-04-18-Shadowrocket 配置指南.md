---
layout: post
title: "Shadowrocket 设置教程 (Updated, for 2.0.5)"
date: "2016-04-18 15:22:51 +0800"
categories: gfw
published: true
---



### 写在前面    
首先你需要这个软件Shadowrocket这个软件基本上是一个本地代理（类似Surge），通过事先写好的规则‘自动’判断网络流量走向（shadowsocks加密通道（爬墙通道），服务加速通道（apple），直接连接）
你还需要一个Shadowsocks账号，自己搭或者去购买

### 开始
1. 下载App [点我](https://itunes.apple.com/us/app/shadowrocket-for-shadowsocks/id932747118?mt=8#) （这是美国区的）[点我](https://appsto.re/cn/UDjM3.i)(中国区），有条件尽量买美国区的。    

2. 打开app，进入主界面，我们一共要配置2个地方，一个是shadowsocks服务器配置，一个是Surge规则配置。我们首先点击Setting，进入Surge规则设置界面。![main][6]    

3. 点击Config，进入Surge Config配置界面，![Surge][2]    然后点击右上的+号![log][3]    输入配置文件地址*https://raw.githubusercontent.com/zgli1980/surge_conf/master/main.conf*<b style="color: red">（这里要替换成你自己的配置文件地址）</b>，输完后点击Download。![url][9]    ，或者直接扫描二维码![qrcode2][10]

4. 接下来在REMOTE FILES这一栏就出现了你刚才输入的配置文件地址，点击地址，选择Use Config。![use config][4]    

5. 我们需要确认一些配置文件是否正确加载了，LOCAL这里出现main或你自己的配置文件标示配置文件正确家在，选择你的配置文件（前有有勾）。![verify][5]     

6. 回到上一界面，进入Proxy设置，把logging打开。![log][7]  

7. 这样Surge规则配置就OK了，下面我们来设置Shadowsocks，回到主界面，点击右上角+号进入Shadowsocks配置界面![ss config][1]     按下图填入服务器信息![ss server][8]    或者直接扫描二维码（点击左上角打开二维码扫描）

8. 接下来打开VPN开关，尽情享受自由的互联网吧。

[1]:https://raw.githubusercontent.com/zgli1980/zgli1980.github.io/master/_src/20160418_ShadowRocket/IMG_1177.PNG         
[2]:https://raw.githubusercontent.com/zgli1980/zgli1980.github.io/master/_src/20160418_ShadowRocket/IMG_1178.PNG         
[3]:https://raw.githubusercontent.com/zgli1980/zgli1980.github.io/master/_src/20160418_ShadowRocket/IMG_1179.PNG         
[4]:https://raw.githubusercontent.com/zgli1980/zgli1980.github.io/master/_src/20160418_ShadowRocket/IMG_1180.PNG         
[5]:https://raw.githubusercontent.com/zgli1980/zgli1980.github.io/master/_src/20160418_ShadowRocket/IMG_1181.PNG         
[6]:https://raw.githubusercontent.com/zgli1980/zgli1980.github.io/master/_src/20160418_ShadowRocket/IMG_1182.PNG         
[7]:https://raw.githubusercontent.com/zgli1980/zgli1980.github.io/master/_src/20160418_ShadowRocket/IMG_1183.PNG         
[8]:https://raw.githubusercontent.com/zgli1980/zgli1980.github.io/master/_src/20160418_ShadowRocket/IMG_1184.PNG         
[9]:https://raw.githubusercontent.com/zgli1980/zgli1980.github.io/master/_src/20160323_shadowrocket/8.PNG        
[10]:https://raw.githubusercontent.com/zgli1980/zgli1980.github.io/master/_src/20160418_ShadowRocket/surge_conf.png        
