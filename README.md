# AAPanel-Linux历史版本更新包存档
本仓库所有版本的更新包通过 `node.aapanel.com` 下载

AAPanel 7.0.28正式版更新日志：[https://www.aapanel.com/forum/d/25157-aapanel-7028-released-on-25-nov-2025](https://www.aapanel.com/forum/d/25157-aapanel-7028-released-on-25-nov-2025)<br/>

本仓库仅保存AApanel v6.8.24及之后的更新包，获取地址均在：node.aapanel.com

<!-- * 6.8.37及以后的版本，站点404＆502错误页上有 aapanel 的AD -->

CentOS 7 已达到使用寿命，社区支持于2024年6月30日结束，建议您使用 Ubuntu22.04 安装 AAPanel

## 一键安装脚本

### V7.0 Free
```
URL=https://www.aapanel.com/script/install_7.0_en.sh && if [ -f /usr/bin/curl ];then curl -ksSO "$URL" ;else wget --no-check-certificate -O install_7.0_en.sh "$URL";fi;bash install_7.0_en.sh aapanel
```
### V7.0 Pro
```
URL=https://www.aapanel.com/script/install_pro_en.sh && if [ -f /usr/bin/curl ];then curl -ksSO $URL ;else wget --no-check-certificate -O install_pro_en.sh $URL;fi;bash install_pro_en.sh aa372544
```
