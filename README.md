# AAPanel-Linux
AAPanel（宝塔面板国际版）安装脚本<br/><br/>
AAPanel 7.0.6正式版更新日志：[https://www.aapanel.com/forum/d/20972-aapanel-706-released-on-02-jul-2024](https://www.aapanel.com/forum/d/20972-aapanel-706-released-on-02-jul-2024)<br/>
AAPanel 7.6.0 Beta更新日志：[https://www.aapanel.com/forum/d/21077-aapanel-760-beta-released-on-11-jul-2024](https://www.aapanel.com/forum/d/21077-aapanel-760-beta-released-on-11-jul-2024)

* 7.0安装命令：
```
URL=https://www.aapanel.com/script/install_7.0_en.sh && if [ -f /usr/bin/curl ];then curl -ksSO "$URL" ;else wget --no-check-certificate -O install_7.0_en.sh "$URL";fi;bash install_7.0_en.sh aapanel
```
