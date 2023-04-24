# OpenWrt-PPPoE-Server-Account-Manager
Manages PPPoE Account
-Add, Edit, Delete PPPoE Account in luci.

How to install?<br/>
run opkg update<br/>
copy the command and paste in your teminal (select which architecture for your device) <br/>
<br/>
for mips architecture devices:<br/>
wget -O /tmp/pppoeuser.ipk https://github.com/akosiramnad/OpenWrt-PPPoE-Server-Account-Manager/blob/main/pppoeuser_1.0.0-1_mips_24kc.ipk && opkg install /tmp/pppoeuser.ipk<br/>
<br/>
for ramips architecture devices:<br/>
wget -O /tmp/pppoe-server.ipk https://github.com/akosiramnad/OpenWrt-PPPoE-Server-Account-Manager/blob/main/pppoeuser_1.0.0-1_mipsel_24kc.ipk && opkg install /tmp/pppoeuser.ipk<br/>
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
if installation is success you will see PPPoE Accounts menu under the Services after reboot.
