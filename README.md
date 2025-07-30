# AAPanel-Linux历史版本更新包存档
本仓库所有版本的更新包通过 `node.aapanel.com` 下载

AAPanel 7.0.22正式版更新日志：[https://www.aapanel.com/forum/d/24503-aapanel-7022-released-on-29-jul-2025](https://www.aapanel.com/forum/d/24503-aapanel-7022-released-on-29-jul-2025)<br/>

本仓库仅保存AApanel v6.8.24及之后的更新包，获取地址均在：node.aapanel.com

* 6.8.37及以后的版本，站点404＆502错误页上有 aapanel 的AD

CentOS 7 已达到使用寿命，社区支持于2024年6月30日结束，建议您使用 Ubuntu22.04 安装 AAPanel

* 7.0安装命令：
```
URL=https://www.aapanel.com/script/install_7.0_en.sh && if [ -f /usr/bin/curl ];then curl -ksSO "$URL" ;else wget --no-check-certificate -O install_7.0_en.sh "$URL";fi;bash install_7.0_en.sh aapanel
```
