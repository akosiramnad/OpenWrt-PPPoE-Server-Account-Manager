# OpenWrt-PPPoE-Server-Account-Manager
Manages PPPoE Account<br/>
-Add, Edit, Delete PPPoE Account in luci.

How to install?<br/>
run opkg update<br/>
copy the command and paste in your teminal (select which platform fits for your device) <br/>
<br/>
for mips platform:<br/>
```wget -O /tmp/pppoeuser.ipk https://github.com/akosiramnad/OpenWrt-PPPoE-Server-Account-Manager/blob/main/pppoeuser_1.0.0-1_mips_24kc.ipk && opkg install /tmp/pppoeuser.ipk```<br/>
<br/>
for ramips platform:<br/>
```wget -O /tmp/pppoe-server.ipk https://github.com/akosiramnad/OpenWrt-PPPoE-Server-Account-Manager/blob/main/pppoeuser_1.0.0-1_mipsel_24kc.ipk && opkg install /tmp/pppoeuser.ipk```<br/>
<br/>
configure /etc/config/pppoe<br/>
reboot<br/>
<br/>
or<br/>
<br/>
install rp-pppoe-server<br/>
configure /etc/config/pppoe<br/>
download and install the ipk for your device<br/>
reboot<br/>
<br/>
<br/>

Note:<br/>
if installation is success you will see PPPoE Accounts menu under the Services after reboot.<br/>
![alt text](https://github.com/akosiramnad/OpenWrt-PPPoE-Server-Account-Manager/blob/main/sample.png?raw=true)


 #[Version 2.0]([https://github.com/akosiramnad/OpenWrt-PPPoE-Server-Account-Manager/releases/download/pppoe-user/pppoeuser_v2.0.ipk](https://github.com/akosiramnad/OpenWrt-PPPoE-Server-Account-Manager/releases/tag/pppoeuser_v2)https://github.com/akosiramnad/OpenWrt-PPPoE-Server-Account-Manager/releases/tag/pppoeuser_v2).
![Screenshot 2024-02-10 215450](https://github.com/akosiramnad/OpenWrt-PPPoE-Server-Account-Manager/assets/67589626/f7847fc0-06e2-41c6-86ee-065a453c5521)
