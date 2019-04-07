# 一个逗比写的逗比脚本

## 脚本索引

* [***代理相关***](#代理相关)
  * [ssr.sh](#ssrsh)
  * [ssrmu.sh](#ssrmush)
  * [brook.sh](#brooksh)
  * [goflyway.sh](#goflywaysh)
  * [lightsocks.sh](#lightsockssh)
  * [mtproxy.sh](#mtproxysh)
* [***中转相关***](#中转相关)
  * [iptables-pf.sh](#iptables-pfsh)
  * [brook-pf.sh](#brook-pfsh)
  * [haproxy.sh](#haproxysh)
  * [socat.sh](#socatsh)
  * [tinymapper.sh](#tinymappersh)
* [***BT下载相关***](#bt下载相关)
  * [aria2.sh](#aria2sh)
  * [cloudt.sh](#cloudtsh)
  * [pserver.sh](#pserversh)
* [***服务器相关***](#服务器相关)
  * [bbr.sh](#bbrsh)
  * [status.sh](#statussh)
  * [ban_iptables.sh](#ban_iptablessh)
  * [ssh_port.sh](#ssh_portsh)
* [***VPN 相关***](#vpn相关)
  * [ocserv.sh](#ocservsh)
* [***DNS 相关***](#dns相关)
  * [dowsdns.sh](#dowsdnssh)
* [***HTTP 相关***](#http相关)
  * [caddy_install.sh](#caddy_installsh)
  * [pythonhttp.sh](#pythonhttpsh)
* [***其他***](#其他)
  * [adbyby.sh](#adbybysh)
  * [libsodium.sh](#libsodiumsh)
  * [ssrstatus.sh](#ssrstatussh)
  * [ssr_check.sh](#ssr_checksh)
  * [ssr_ip_check.sh](#ssr_ip_checksh)

---

## 代理相关

## ssr.sh

- 脚本说明: ShadowsocksR 一键安装/管理脚本，支持单端口/多端口切换和管理
- 系统支持: CentOS6+ / Debian6+ / Ubuntu14+
- 使用方法: https://doub.io/ss-jc42/
- 项目地址: https://github.com/ToyoDAdoubi/shadowsocksr

#### 脚本特点:
目前网上的各个ShadowsocksR脚本基本都是只有 安装/启动/重启 等基础功能，对于小白来说还是不够简单方便。既然是一键脚本，那么就要尽可能地简单，小白更容易接受使用！

- 支持 限制 用户速度
- 支持 限制 端口设备数
- 支持 显示 当前连接IP
- 支持 显示 SS/SSR连接+二维码
- 支持 切换管理 单/多端口
- 支持 一键安装 锐速
- 支持 一键安装 BBR
- 支持 一键封禁 垃圾邮件(SMAP)/BT/PT

#### 下载安装:
``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/moranchenxi/moran/master/ssr.sh && chmod +x ssr.sh && bash ssr.sh
```

---
## ssrmu.sh

- 脚本说明: ShadowsocksR 一键安装/管理脚本，支持流量控制
- 系统支持: CentOS6+ / Debian6+ / Ubuntu14+
- 使用方法: https://doub.io/ss-jc60/
- 项目地址: https://github.com/ToyoDAdoubi/shadowsocksr

#### 脚本特点:
目前网上的各个ShadowsocksR脚本基本都是只有 安装/启动/重启 等基础功能，对于小白来说还是不够简单方便。既然是一键脚本，那么就要尽可能地简单，小白更容易接受使用！

- 支持 限制 用户速度
- 支持 限制 用户设备数
- 支持 限制 用户总流量
- 支持 定时 流量清零
- 支持 显示 当前连接IP
- 支持 显示 SS/SSR连接+二维码
- 支持 一键安装 锐速
- 支持 一键安装 BBR
- 支持 一键封禁 垃圾邮件(SMAP)/BT/PT

#### 下载安装:
``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/moranchenxi/moran/master/ssrmu.sh && chmod +x ssrmu.sh && bash ssrmu.sh
```

---
## brook.sh

- 脚本说明: Brook 一键安装脚本
- 系统支持: CentOS6+ / Debian7+ / Ubuntu14+
- 使用方法: https://doub.io/brook-jc3/

#### 下载安装:
``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/moranchenxi/moran/master/brook.sh && chmod +x brook.sh && bash brook.sh
```

---
## goflyway.sh

- 脚本说明: GoFlyway 一键安装脚本
- 系统支持: CentOS6+ / Debian7+ / Ubuntu14+
- 使用方法: https://doub.io/goflyway-jc2/

#### 下载安装:
``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/moranchenxi/moran/master/goflyway.sh && chmod +x goflyway.sh && bash goflyway.sh
```

---
## lightsocks.sh

- 脚本说明: LightSocks 一键安装脚本
- 系统支持: CentOS6+ / Debian7+ / Ubuntu14+
- 使用方法: https://doub.io/lightsocks-jc1/

#### 下载安装:
``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/moranchenxi/moran/master/lightsocks.sh && chmod +x lightsocks.sh && bash lightsocks.sh
```

---
## mtproxy.sh

- 脚本说明: Mtproto Proxy 一键安装脚本
- 系统支持: CentOS7 / Debian7+ / Ubuntu14+
- 使用方法: https://doub.io/shell-jc7/

#### 下载安装:
``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/moranchenxi/moran/master/mtproxy.sh && chmod +x mtproxy.sh && bash mtproxy.sh
```

---

## 中转相关

## iptables-pf.sh

- 脚本说明: iptables 端口转发 一键安装/管理脚本
- 系统支持: CentOS6+ / Debian6+ / Ubuntu14+
- 使用方法: https://doub.io/wlzy-20/

#### 下载安装:
``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/moranchenxi/moran/master/iptables-pf.sh && chmod +x iptables-pf.sh && bash iptables-pf.sh
```

---
## brook-pf.sh

- 脚本说明: Brook 端口转发 一键安装/管理脚本
- 系统支持: CentOS6+ / Debian6+ / Ubuntu14+
- 使用方法: https://doub.io/wlzy-37/

#### 下载安装:
``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/moranchenxi/moran/master/brook-pf.sh && chmod +x brook-pf.sh && bash brook-pf.sh
```

---
## haproxy.sh

- 脚本说明: HaProxy 一键安装/管理脚本
- 系统支持: CentOS6+ / Debian6+ / Ubuntu14+
- 使用方法: https://doub.io/wlzy-19/

#### 下载安装:
``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/moranchenxi/moran/master/haproxy.sh && chmod +x haproxy.sh && bash haproxy.sh
```

---
## socat.sh

- 脚本说明: Socat 一键安装/管理脚本
- 系统支持: CentOS6+ / Debian6+ / Ubuntu14+
- 使用方法: https://doub.io/wlzy-18/

#### 下载安装:
``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/moranchenxi/moran/master/socat.sh && chmod +x socat.sh && bash socat.sh
```

---
## tinymapper.sh

- 脚本说明: tinyPortMapper 一键安装/管理脚本
- 系统支持: CentOS6+ / Debian6+ / Ubuntu14+
- 使用方法: https://doub.io/wlzy-36/

#### 下载安装:
``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/moranchenxi/moran/master/tinymapper.sh && chmod +x tinymapper.sh && bash tinymapper.sh
```

---

## BT下载相关

## aria2.sh

- 脚本说明: Aria2 一键安装脚本
- 系统支持: CentOS6+ / Debian6+ / Ubuntu14+
- 使用方法: https://doub.io/shell-jc4/

#### 下载安装:
``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/moranchenxi/moran/master/aria2.sh && chmod +x aria2.sh && bash aria2.sh
```

---
## cloudt.sh

- 脚本说明: Cloud Torrent 一键安装脚本
- 系统支持: CentOS6+ / Debian6+ / Ubuntu14+
- 使用方法: https://doub.io/wlzy-12/
- 项目地址: https://github.com/jpillora/cloud-torrent

#### 下载安装:
``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/moranchenxi/moran/master/cloudt.sh && chmod +x cloudt.sh && bash cloudt.sh
```

---
## pserver.sh

- 脚本说明: Peerflix Server 一键安装脚本
- 系统支持: CentOS6+ / Debian6+ / Ubuntu14+
- 使用方法: https://doub.io/wlzy-13/
- 项目地址: https://github.com/asapach/peerflix-server

#### 下载安装:
``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/moranchenxi/moran/master/pserver.sh && chmod +x pserver.sh && bash pserver.sh
```

---

## 服务器相关

## bbr.sh

- 脚本说明: BBR 一键安装脚本
- 系统支持: Debian6+ / Ubuntu14+
- 使用方法: https://doub.io/wlzy-16/

#### 下载安装:
``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/moranchenxi/moran/master/bbr.sh && chmod +x bbr.sh && bash bbr.sh
```

---
## status.sh

- 脚本说明: ServerStatus 一键安装/管理脚本
- 系统支持: CentOS6+ / Debian6+ / Ubuntu14+
- 使用方法: https://doub.io/shell-jc3/

#### 下载安装:
``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/moranchenxi/moran/master/status.sh && chmod +x status.sh && bash status.sh
```

---
## ban_iptables.sh

- 脚本说明: iptables 垃圾邮件(SPAM)/BT/PT 一键封禁脚本
- 系统支持: CentOS6+ / Debian6+ / Ubuntu14+
- 使用方法: https://doub.io/shell-jc2/

#### 下载安装:
``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/moranchenxi/moran/master/ban_iptables.sh && chmod +x ban_iptables.sh && bash ban_iptables.sh
```

---
## ssh_port.sh

- 脚本说明: SSH 一键修改端口脚本
- 系统支持: Debian6+ / Ubuntu14+
- 使用方法: https://doub.io/linux-jc11/

#### 下载安装:
``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/moranchenxi/noran/master/ssh_port.sh && chmod +x ssh_port.sh && bash ssh_port.sh
```

---

## VPN相关

## ocserv.sh

- 脚本说明: Ocserv AnyConnect 一键安装脚本
- 系统支持: Debian7+ / Ubuntu14+
- 使用方法: https://doub.io/vpnzy-7/

#### 下载安装:
``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/moranchenxi/moran/master/ocserv.sh && chmod +x ocserv.sh && bash ocserv.sh
```

---

## DNS相关

## dowsdns.sh

- 脚本说明: DowsDNS 一键安装脚本
- 系统支持: CentOS7 / Debian7+ / Ubuntu14+
- 使用方法: https://doub.io/dowsdns-jc3/

#### 下载安装:
``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/moranchenxi/moran/master/dowsdns.sh && chmod +x dowsdns.sh && bash dowsdns.sh
```

---

## HTTP相关

## caddy_install.sh

- 脚本说明: Caddy 一键安装脚本
- 系统支持: CentOS6+ / Debian7+ / Ubuntu14+
- 使用方法: https://doub.io/shell-jc1

#### 下载安装:
``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/moranchenxi/moran/master/caddy_install.sh && chmod +x caddy_install.sh && bash caddy_install.sh
 # 安装插件：
 bash caddy_install.sh xxx,xxx
  # 例如同时安装 http.filemanager 和 http.webdav插件：
  bash caddy_install.sh http.filemanager,http.webdav
  # 插件和Caddy是集成在一起的(单个二进制文件)，多个插件必须同时安装。
# 卸载命令：
wget -N --no-check-certificate https://raw.githubusercontent.com/moranchenxi/moran/master/caddy_install.sh && chmod +x caddy_install.sh && caddy_install.sh uninstall
利用caddy反代网站
以下所有示例域名为toyoo.ml，请注意替换为自己的域名 ！

1、服务器IP反向代理
下面是一个，用你服务器的IP来反向代理一个http协议的网站http://www.baidu.com 。

# 以下全部内容是一个整体，是一个命令，全部复制粘贴到SSH软件中并一起执行！
echo ":80 {
 gzip
 proxy / http://www.baidu.com
}" > /usr/local/caddy/Caddyfile
服务器IP也可以反向代理HTTPS协议的网站，但是需要自签SSL证书，现在的浏览器一般都不会认自签的SSL证书，所以不建议这么做。

2、域名反向代理HTTP
下面是一个，用你的域名来反向代理一个http协议的网站http://www.baidu.com。

# 以下全部内容是一个整体，是一个命令，全部复制粘贴到SSH软件中并一起执行！
echo "http://toyoo.ml {
 gzip
 proxy / http://www.baidu.com
}" > /usr/local/caddy/Caddyfile
如果你需要反向代理HTTPS协议的网站，比如https://www.baidu.com，那么继续看下面步骤。

3、域名反向代理HTTPS
如果你有SSL证书和密匙的话，把SSL证书(xxx.crt)和密匙(xxx.key)文件放到/root文件夹下（也可以是其他文件夹，自己改下面代码），然后这样做：

# 以下全部内容是一个整体，是一个命令，全部复制粘贴到SSH软件中并一起执行！
echo "https://toyoo.ml {
 gzip
 tls /root/xxx.crt /root/xxx.key
 proxy / https://www.baidu.com
}" > /usr/local/caddy/Caddyfile
如果你没有SSL证书和密匙，那么你可以这样做：

下面的xxxx@xxx.xx改成你的邮箱，同时需要注意的是，申请SSL证书前，请务必提前解析好域名记录(解析后最好等一会，以全球生效)，否则Caddy会申请并配置失败！

# 以下全部内容是一个整体，是一个命令，全部复制粘贴到SSH软件中并一起执行！
echo "https://toyoo.ml {
 gzip
 tls xxxx@xxx.xx
 proxy / https://www.baidu.com
}" > /usr/local/caddy/Caddyfile
如果一切正常，那么Caddy会自动帮你申请SSL证书并配置好，而且会定时续约SSL证书和强制http重定向至https！

4、HTTP重定向为HTTPS
当你是手动指定SSL证书和密匙 来配置的话，Caddy只会监听443端口(https)，并不会自动设置80端口(http)的重定向（如果是Caddy自动申请的SSL证书，那么就自动做好了），如果要做重定向的话，可以这样做：

下面的示例代码中，是把http://toyoo.ml、http://233.toyoo.ml、https://666.toyoo.ml三个域名都重定向到了 https://toyoo.ml。

# 以下全部内容是一个整体，是一个命令，全部复制粘贴到SSH软件中并一起执行！
echo "http://toyoo.ml ,http://233.toyoo.ml ,https://666.toyoo.ml {
 redir https://toyoo.ml{url}
}
https://toyoo.ml {
 gzip
 tls /root/xxx.crt /root/xxx.key
 proxy / https://www.baidu.com
}" > /usr/local/caddy/Caddyfile
修改完Caddy的配置文件后，重启Caddy即可。

/etc/init.d/caddy restart
```

---
## pythonhttp.sh

- 脚本说明: SimpleHTTPServer 一键安装/管理脚本
- 系统支持: CentOS6+ / Debian6+ / Ubuntu14+
- 使用方法: https://doub.io/wlzy-8/

#### 下载安装:
``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/moranchenxi/moran/master/pythonhttp.sh && chmod +x pythonhttp.sh && bash pythonhttp.sh
```

---

## 其他

## adbyby.sh

- 脚本说明: ADbyby 一键安装脚本
- 系统支持: CentOS6+ / Debian6+ / Ubuntu14+
- 使用方法: https://doub.io/adbyby-jc2/

#### 下载安装:
``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/moranchenxi/moran/master/adbyby.sh && chmod +x adbyby.sh && bash adbyby.sh
```

---
## libsodium.sh

- 脚本说明: libsodium 一键安装脚本
- 系统支持: CentOS6+ / Debian6+ / Ubuntu14+
- 使用方法: https://doub.io/shell-jc6/

#### 下载安装:
``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/moranchenxi/moran/master/libsodium.sh && chmod +x libsodium.sh && bash libsodium.sh
```

---
## ssr_check.sh

- 脚本说明: ShadowsocksR 批量快速验证账号可用性
- 系统支持: CentOS6+ / Debian6+ / Ubuntu14+
- 使用方法: https://doub.io/ss-jc56/

#### 下载安装:
``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/moranchenxi/moran/master/ssr_check.sh && chmod +x ssr_check.sh
```

---
## ssrstatus.sh

- 脚本说明: ShadowsocksR 账号在线监控网站
- 系统支持: CentOS6+ / Debian6+ / Ubuntu14+
- 使用方法: https://doub.io/shell-jc5/

#### 下载安装:
``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/moranchenxi/moran/master/ssrstatus.sh && chmod +x ssrstatus.sh && bash ssrstatus
```

---
## ssr_ip_check.sh

- 脚本说明: ShadowsocksR 检测每个端口链接IP数
- 系统支持: CentOS6+ / Debian6+ / Ubuntu14+
- 使用方法: https://doub.io/ss-jc50/

#### 下载安装:
``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/moranchenxi/moran/master/ssr_ip_check.sh && chmod +x ssr_ip_check.sh
```

---
## ~~pipes.sh~~

- 脚本说明: PipeSocks 一键安装脚本（该软件已停更）
- 系统支持: CentOS7 / Debian7+ / Ubuntu14+
- 使用方法: https://doub.io/pipesocks-jc2/

#### 下载安装:
``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/pipesocks/install/master/install.sh && mv install.sh pipes.sh && chmod +x pipes.sh && bash pipes.sh
```

---
## ~~gogo.sh~~

- 脚本说明: GoGo Tunnel 一键安装脚本（该软件已停更）
- 系统支持: CentOS6+ / Debian6+ / Ubuntu14+
- 使用方法: https://doub.io/wlzy-24/

#### 下载安装:
``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/moranchenxi/moran/master/gogo.sh && chmod +x gogo.sh && bash gogo.sh
```

---
Copyright (C) 2016-2018 Toyo <https://doub.io>
