# OpenWrt-PPPoE-Server-Account-Manager
Manages PPPoE Account
-Add, Edit, Delete PPPoE Account in luci.

How to install?
run opkg update
copy the link and paste in your teminal (select which architecture for your device) 

for mips architecture devices
wget -O /tmp/pppoeuser.ipk https://github.com/akosiramnad/OpenWrt-PPPoE-Server-Account-Manager/blob/main/pppoeuser_1.0.0-1_mips_24kc.ipk && opkg install /tmp/pppoeuser.ipk

for ramips architecture devices
wget -O /tmp/pppoe-server.ipk https://github.com/akosiramnad/OpenWrt-PPPoE-Server-Account-Manager/blob/main/pppoeuser_1.0.0-1_mipsel_24kc.ipk && opkg install /tmp/pppoeuser.ipk

configure /etc/config/pppoe
reboot

or

install rp-pppoe-server
configure /etc/config/pppoe
download and install the ipk for your device
reboot


Note:
if installation is success you will see PPPoE Accounts menu under the Services after reboot.
