# HC5661-OpenWrt-Patch
A Patch for HiWiFi HC5661 OpenWrt

HiWiFi HC5661 OpenWrt编译补丁

默认管理地址：192.168.1.1:88

默认管理密码：admin

# 使用方法：

cd trunk

patch -p1 < HC5661.patch

make menuconfig

make V=99
