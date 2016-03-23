
### 写在前面    
首先你需要一个Shadowsocks账号，这个软件基本上是一个本地代理（类似Surge），通过事先写好的规则‘自动’判断网络流量走向（shadowsocks加密通道（爬墙通道），服务加速通道（apple），直接连接）

### 开始
1. 下载App [点我](https://itunes.apple.com/us/app/shadowrocket-for-shadowsocks/id932747118?mt=8#) （这是美国区的，中国区已下架）
2. 打开app，进入主界面，我们一共要配置2个地方，一个是shadowsocks服务器配置，一个是Surge规则配置。我们首先点击Setting，进入Surge规则设置界面。<img  style="max-width: 100%"; src="https://raw.githubusercontent.com/zgli1980/markdown_pics/master/shadowrocket/1.jpg"  >
3. 点击Surge，进入Surge配置界面，![setting][2]   <br>然后点击右上的+号，输入配置文件地址*http://fuckgfw.com/main.conf*<b style="color: red">（这里要替换成你自己的配置文件地址）</b>，输完后点击Download。
4. 接下来在REMOTE CONFIG这一栏就出现了你刚才输入的配置文件地址，点击地址，选择Use Config。![surge][3]
5. 我们需要确认一些配置文件是否正确加载了，点击Modify Config...，确认是否是你的配置文件。![verify][4]
6. 回到上一界面，进入Proxy设置，把logging打开。![log][5]
7. 这样Surge规则配置就OK了，下面我们来设置Shadowsocks，回到主界面，点击右上角+号进入Shadowsocks配置界面，按下图填入你的服务器信息  ![ss][6]
8. 接下来打开VPN开关，尽情享受自由的互联网吧。


[1]: https://raw.githubusercontent.com/zgli1980/markdown_pics/master/shadowrocket/1.jpg  "main"
[2]: https://raw.githubusercontent.com/zgli1980/markdown_pics/master/shadowrocket/2.jpg  "setting"
[3]: https://raw.githubusercontent.com/zgli1980/markdown_pics/master/shadowrocket/3.jpg  "surge"
[4]: https://raw.githubusercontent.com/zgli1980/markdown_pics/master/shadowrocket/4.jpg  "verify"
[5]: https://raw.githubusercontent.com/zgli1980/markdown_pics/master/shadowrocket/5.jpg  "log"
[6]: https://raw.githubusercontent.com/zgli1980/markdown_pics/master/shadowrocket/6.PNG  "ss"
[7]: https://raw.githubusercontent.com/zgli1980/markdown_pics/master/shadowrocket/7.PNG  "surge_add"
[8]: https://raw.githubusercontent.com/zgli1980/markdown_pics/master/shadowrocket/8.PNG  "surge_download"
[9]: https://raw.githubusercontent.com/zgli1980/markdown_pics/master/shadowrocket/9.PNG  "ss_add"
