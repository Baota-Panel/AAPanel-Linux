# AAPanel-Linux
AAPanel（宝塔面板国际版）安装脚本<br/><br/>
AAPanel 6.8.37正式版更新日志：[https://forum.aapanel.com/d/20136-aapanel-6837-released-on-29-apr-2024](https://forum.aapanel.com/d/20136-aapanel-6837-released-on-29-apr-2024)

* 安装命令：
```
URL=https://www.aapanel.com/script/install_6.0_en.sh && if [ -f /usr/bin/curl ];then curl -ksSO "$URL" ;else wget --no-check-certificate -O install_6.0_en.sh "$URL";fi;bash install_6.0_en.sh aapanel
```
