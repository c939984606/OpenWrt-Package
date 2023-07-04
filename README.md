<div align="center">
    <h2 align="center">常用OpenWrt软件包源码合集，同步上游不定时更新！</h2>
    <img src="https://img.shields.io/github/issues/c939984606/OpenWrt-Package?color=green" alt="">
    <img src="https://img.shields.io/github/stars/c939984606/OpenWrt-Package?color=yellow" alt="">
    <img src="https://img.shields.io/github/forks/c939984606/OpenWrt-Package?color=orange" alt="">
    <img src="https://img.shields.io/github/license/c939984606/OpenWrt-Package?color=ff69b4" alt="">
    <img src="https://img.shields.io/github/languages/code-size/c939984606/OpenWrt-Package?color=blueviolet" alt="">
</div>
<br><br>

```
0x1. 推荐指数仅代表个人观点

0x2. 部分插件年代久远，用途不大的插件未收录

0x3. 编译过程如果缺少依赖包，欢迎指正，如需其他插件欢迎留言反馈

0x4. openwrt源码推荐配合 https://github.com/coolsnowwolf/lede 使用

0x5. 部分插件包未找到作者，源码来自 https://github.com/kenzok8/small-package

0x6. 建议路由器不要包含太多的功能，需要某种功能用docker拉取镜像，路由器插件一般更新慢，不要想着All in One
```
<br><br>
<div>

| 名称                           | 推荐指数  | 简介                                              | 源码地址                                                                               |
|------------------------------|-------|-------------------------------------------------|------------------------------------------------------------------------------------|
| **科学**                       |       |                                                 |                                                                                    |
| luci-app-ssr-plus            | ★★★★★ | Lean源码科学插件                                      | [打开](https://github.com/fw876/helloworld.git)                                      |
| luci-app-passwall            | ★★★★★ | 强大的科学插件                                         | [打开](https://github.com/xiaorouji/openwrt-passwall.git)                            |
| luci-app-passwall2           | ★★★   | 强大的科学插件                                         | [打开](https://github.com/xiaorouji/openwrt-passwall2)                               |
| luci-app-openclash           | ★★★★★ | Clash 客户端                                       | [打开](https://github.com/vernesong/OpenClash.git)                                   |
| luci-app-bypass              | ★     | 科学插件                                            | [打开](https://github.com/tianiue/luci-app-bypass.git)                               |
| luci-app-v2raya              | ★★★   | 强大的，跨平台的 V2Ray 客户端                              | [打开](https://github.com/zxlhhyccc/luci-app-v2raya.git)                             |
|                              |       |                                                 |                                                                                    |
| **文件**                       |       |                                                 |                                                                                    |
| luci-app-alist               | ★★★★★ | 强大的网盘挂载工具                                       | [打开](https://github.com/sbwml/luci-app-alist.git)                                  |
| ~~luci-app-baidupcs-web~~    |       | ~~项目废弃~~                                        | [打开](https://github.com/KFERMercer/luci-app-baidupcs-web.git)                      |
| luci-app-fileassistant       | ★★★   | 文件助手，filebrowse的移植版，修改LuCI菜单目录，增加安装 ipk 功能      | [打开](https://github.com/shidahuilang/luci-app-fileassistant.git)                   |
| luci-app-filebrowser         | ★★★   | filebrowse文件管理                                  | [打开](https://github.com/c939984606/small-package/tree/main/luci-app-filebrowser)   |
| luci-app-kodexplorer         | ★★★   | 可道云                                             | [打开](https://github.com/c939984606/small-package/tree/main/luci-app-kodexplorer)   |
| luci-app-nextcloud           | ★★★   | nextcloud网盘                                     | [打开](https://github.com/c939984606/small-package/tree/main/luci-app-nextcloud)     |
| luci-app-webd                | ★★★   | 轻量级(self-hosted)自建网盘软件                          | [打开](https://github.com/c939984606/small-package/tree/main/luci-app-webd)          |
|                              |       |                                                 |                                                                                    |
| **加速器**                      |       |                                                 |                                                                                    |
| luci-app-LingTiGameAcc       | ★★    | 灵缇游戏加速器                                         | [打开](https://github.com/esirplayground/luci-app-LingTiGameAcc.git)                 |
| luci-app-UUGameAcc           | ★★    | UU加速五合一插件                                       | [打开](https://github.com/BCYDTZ/luci-app-UUGameAcc.git)                             |
| luci-app-xunyou              | ★★    | 迅游加速器                                           | [打开](https://github.com/c939984606/OpenWrt-Package/tree/main/luci-app-xunyou)      |
|                              |       |                                                 |                                                                                    |
| **去广告**                      |       |                                                 |                                                                                    |
| luci-app-adguardhome         | ★★★★★ | 去广告插件                                           | [打开](https://github.com/c939984606/OpenWrt-Package/tree/main/luci-app-adguardhome) |
| luci-app-dnsfilter           | ★★    | 基于DNS的广告过滤,(基于dnsmasq-full与dnsmasq冲突)           | [打开](https://github.com/kiddin9/luci-app-dnsfilter.git)                            |
|                              |       |                                                 |                                                                                    |
| **主题**                       |       |                                                 |                                                                                    |
| luci-app-argon               | ★★★★★ | Argon主题                                         | [打开](https://github.com/jerrykuku/luci-theme-argon.git)                            |
| luci-app-argon-config        | ★★★★★ | Argon主题配置程序                                     | [打开](https://github.com/jerrykuku/luci-app-argon-config.git)                       |
|                              |       |                                                 |                                                                                    |
| **测速**                       |       |                                                 |                                                                                    |
| luci-app-cloudflarespeedtest | ★★★   | 定时执行Cloudflare IP速度测试                           | [打开](https://github.com/mingxiaoyu/luci-app-cloudflarespeedtest.git)               |
|                              |       |                                                 |                                                                                    |
| **网络**                       |       |                                                 |                                                                                    |
| luci-app-ddns-go             | ★★★★★ | DDNS自动解析，支持阿里云，腾讯云，Cloudflare，华为云，百度云等          | [打开](https://github.com/sirpdboy/luci-app-ddns-go.git)                             |
| luci-app-ddnsto              | ★★★★  | ddnsto穿透解析                                      | [打开](https://github.com/Cookiesnob/luci-app-ddnsto.git)                            |
| luci-app-npc                 | ★★★   | NPS内网穿透客户端                                      | [打开](https://github.com/c939984606/small-package/tree/main/luci-app-npc)           |
| luci-app-openvpn-server      | ★★★   | openvpn服务端，修正了makefile，方便导入feeds 编译             | [打开](https://github.com/hyperlook/luci-app-openvpn-server.git)                     |
| luci-app-pptp-server         | ★★★   | PPTP 服务器                                        | [打开](https://github.com/c939984606/OpenWrt-Package/tree/main/luci-app-pptp-server) |
| luci-app-socat               | ★★★★  | 同时兼容firewall3/4 的luci-app-socat                 | [打开](https://github.com/chenmozhijin/luci-app-socat.git)                           |
| luci-app-softethervpn        | ★★★   | 虚拟专用网络                                          | [打开](https://github.com/c939984606/small-package/tree/main/luci-app-softethervpn)  |
|                              |       |                                                 |                                                                                    |
| **系统**                       |       |                                                 |                                                                                    |
| luci-app-advanced            | ★★★★  | 高级设置，包括smartdns，openclash，防火墙，DHCP等             | [打开](https://github.com/c939984606/OpenWrt-Package/tree/main/luci-app-advanced)    |
| luci-app-amlogic             | ★★★   | 晶晨宝盒（支持晶晨s9xxx系列）                               | [打开](https://github.com/ophub/luci-app-amlogic.git)                                |
| luci-app-modemband           | ★★    | 4G LTE频段设置                                      | [打开](https://github.com/4IceG/luci-app-modemband.git)                              |
| luci-app-autoreboot          | ★★★★★ | 自动重启                                            | [打开](https://github.com/c939984606/OpenWrt-Package/tree/main/luci-app-autoreboot)  |
| luci-app-autotimeset         | ★★★★★ | 定时任务                                            | [打开](https://github.com/sirpdboy/luci-app-autotimeset.git)                         |
| luci-app-autoupdate          | ★★★   | 自动更新固件（需搭配build-actions使用）                      | [打开](https://github.com/281677160/luci-app-autoupdate.git)                         |
| luci-app-eqos                | ★★★   | 简单的QoS流控插件                                      | [打开](https://github.com/c939984606/small-package/tree/main/luci-app-eqos)          |
| luci-app-macvlan             | ★★★★  | 创建虚拟网口                                          | [打开](https://github.com/ParticleG/luci-app-macvlan.git)                            |
| luci-app-netdata             | ★★★★  | 系统监控汉化版                                         | [打开](https://github.com/sirpdboy/luci-app-netdata.git)                             |
| luci-app-poweroff            | ★★★★★ | 关闭Openwrt系统                                     | [打开](https://github.com/esirplayground/luci-app-poweroff.git)                      |
| luci-app-poweroffdevice      | ★★★★★ | 一款基于OPNEWRT编译的关机源码插件                            | [打开](https://github.com/sirpdboy/luci-app-poweroffdevice.git)                      |
| luci-app-ramfree             | ★★★★  | 释放系统内存                                          | [打开](https://github.com/chinaboy2345/luci-app-ramfree.git)                         |
|                              |       |                                                 |
| **工具**                       |       |                                                 |                                                                                    |
| luci-app-airconnect          | ★★    | 使用AirPlay将音频发送到UPnP/Sonos/Chromecast播放器         | [打开](https://github.com/c939984606/OpenWrt-Package/tree/main/luci-app-airconnect)  |
| luci-app-aliddns             | ★★★   | 阿里云DDNS                                         | [打开](https://github.com/honwen/luci-app-aliddns.git)                               |
| luci-app-autorepeater        | ★★    | 自动中继器                                           | [打开](https://github.com/peter-tank/luci-app-autorepeater.git)                      |
| luci-app-bridge              | ★★    | 透明网桥                                            | [打开](https://github.com/chen8665272/luci-app-bridge.git)                           |
| luci-app-cloudflarespeedtest | ★★★★  | 定时执行Cloudflare IP 速度测试                          | [打开](https://github.com/mingxiaoyu/luci-app-cloudflarespeedtest.git)               |
| luci-app-cupsd               | ★★★   | USB 打印服务器（支持苹果手机）                               | [打开](https://github.com/sirpdboy/luci-app-cupsd.git)                               |
| luci-app-dnscrypt-proxy2     | ★★★   | DNS代理                                           | [打开](https://github.com/peter-tank/luci-app-dnscrypt-proxy2.git)                   |
| luci-app-dnsmasq-ipset       | ★★    | dnsmasq-full IPSet 的 LuCI 控制界面, 方便用户实现根据域名路由    | [打开](https://github.com/lvqier/luci-app-dnsmasq-ipset.git)                         |
| luci-app-dockerman           | ★★★★★ | 一个用于管理 Docker 容器、镜像、网络、存储卷的 Openwrt 插件          | [打开](https://github.com/lisaac/luci-app-dockerman.git)                             |
| luci-app-easymesh            | ★★    | 基于kmod-batman-adv+802.11s 有线+无线回程的mesh luci设置插件 | [打开](https://github.com/ntlf9t/luci-app-easymesh.git)                              |
| luci-app-easyupdate          | ★★    | 主要用于使用P3TERX/Actions-OpenWrt自动编译固件后的一键更新        | [打开](https://github.com/c939984606/small-package/tree/main/luci-app-easyupdate)    |
| luci-app-emby                | ★★    | OpenWrt上运行emby服务器                               | [打开](https://github.com/c939984606/small-package/tree/main/luci-app-emby)          |
| luci-app-godproxy            | ★★★★  | GodProxy是基于koolproxyR Plus+重新整理而来               | [打开](https://github.com/tcsr200722/luci-app-godproxy.git)                          |
| luci-app-guest-wifi          | ★★★   | 访客网络                                            | [打开](https://github.com/c939984606/small-package/tree/main/luci-app-guest-wifi)    |
| luci-app-homebridge          | ★★★   | 智能家庭网关                                          | [打开](https://github.com/shanglanxin/luci-app-homebridge.git)                       |
| luci-app-ikoolproxy          | ★★★   | iKoolProxy是 Beginner-Go 大神基于koolproxyR重新整理而来的   | [打开](https://github.com/ilxp/luci-app-ikoolproxy.git)                              |
| luci-app-iptvhelper          | ★★★   | iptv                                            | [打开](https://github.com/c939984606/small-package/tree/main/luci-app-iptvhelper)    |
| luci-app-istorex             | ★★★   | 打造类似iStoreOS固件一样的界面                             | [打开](https://github.com/c939984606/small-package/tree/main/luci-app-istorex)       |
| luci-app-jackett             | ★★★   | 一款免费开源跨平台的资源聚合搜索软件                              | [打开](https://github.com/c939984606/small-package/tree/main/luci-app-jackett)       |
| luci-app-jellyfin            | ★★★   | 多媒体服务器                                          | [打开](https://github.com/c939984606/small-package/tree/main/luci-app-jellyfin)      |
| luci-app-lucky               | ★★★   | 替代socat主要用于公网IPv6 tcp/udp转内网ipv4,http/https反向代理 | [打开](https://github.com/sirpdboy/luci-app-lucky.git)                               |
| luci-app-mentohust           | ★★★   | 锐捷认证程序（附带支持赛尔认证）                                | [打开](https://github.com/sbwml/luci-app-mentohust.git)                              |
| luci-app-mosdns              | ★★★   | DNS 转发器                                         | [打开](https://github.com/sbwml/luci-app-mosdns.git)                                 |
| luci-app-natter              | ★★★★  | 帮助 Full cone NAT (NAT 1) 用户打开公网 TCP 端口          | [打开](https://github.com/muink/luci-app-natter.git)                                 |
| luci-app-netspeedtest        | ★★★★  | luci-app-netspeedtest 网络速度诊断测试                  | [打开](https://github.com/sirpdboy/netspeedtest.git)                                 |
| luci-app-nginx-manager       | ★★★   | 更方便的管理openwrt的nginx                             | [打开](https://github.com/sun-cut/luci-app-nginx-manager.git)                        |
| luci-app-oled                | ★★★   | NanoPi R2S openwrt SSD 1306 0.91' oled 显示屏支持    | [打开](https://github.com/NateLol/luci-app-oled.git)                                 |
| luci-app-partexp             | ★★★★  | 一键自动格式化分区、扩容、自动挂载插件                             | [打开](https://github.com/sirpdboy/luci-app-partexp.git)                             |
| luci-app-plex                | ★★★   | 多媒体服务器                                          | [打开](https://github.com/c939984606/small-package/tree/main/luci-app-plex)          |
| luci-app-pppoe-server        | ★★    | PPPoE 服务器                                       | [打开](https://github.com/c939984606/small-package/tree/main/lluci-app-pppoe-server) |
| luci-app-pppoe-relay         | ★★    | PPPoE NAT穿透 点对点协议（PPP）                          | [打开](https://github.com/c939984606/small-package/tree/main/lluci-app-pppoe-relay)  |
| luci-app-pushbot             | ★★★★  | 全能消息推送插件                                        | [打开](https://github.com/zzsj0928/luci-app-pushbot.git)                             |
| luci-app-rtorrent            | ★★    | BT下载工具                                          | [打开](https://github.com/wolandmaster/luci-app-rtorrent.git)                        |
| luci-app-serverchan          | ★★★   | 消息推送插件                                          | [打开](https://github.com/c939984606/small-package/tree/main/luci-app-serverchan)    |
| luci-app-shortcutmenu        | ★★    | 网页快捷菜单用于提供网页的快捷入口（网址导航）                         | [打开](https://github.com/doushang/luci-app-shortcutmenu.git)                        |
| luci-app-smartdns            | ★★★★  | 智能的DNS分流插件                                      | [打开](https://github.com/pymumu/luci-app-smartdns.git)                              |
| luci-app-speedtest-web       | ★★★★  | 内网测速网页版                                         | [打开](https://github.com/ZeaKyX/luci-app-speedtest-web.git)                         |
| luci-app-store               | ★★★★  | iStoreOS 应用商店                                   | [打开](https://github.com/c939984606/small-package/tree/main/luci-app-store)         |
| luci-app-timecontrol         | ★★★   | 家长时间控制                                          | [打开](https://github.com/c939984606/small-package/tree/main/luci-app-timecontrol)   |
| luci-app-unblockneteasemusic | ★★★★  | 解除网易云音乐播放限制                                     | [打开](https://github.com/UnblockNeteaseMusic/luci-app-unblockneteasemusic.git)      |
| luci-app-verysync            | ★★★★  | 威力同步                                            | [打开](https://github.com/c939984606/small-package/tree/main/luci-app-verysync)      |
| luci-app-watchcat-plus       | ★★★★  | 官方js版本的luci-app-watchcat移植                      | [打开](https://github.com/gngpp/luci-app-watchcat-plus.git)                          |
| luci-app-xunlei              | ★★★★  | NAS迅雷Beta-OpenWrt移植版（邀请码：网心超牛）                  | [打开](https://github.com/sbwml/luci-app-xunlei.git)                                 |

</div>

<br><br>
![kenzo github stats](https://github-readme-stats.vercel.app/api?username=c939984606&show_icons=true&theme=merko)