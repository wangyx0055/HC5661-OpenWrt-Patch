# HC5661-OpenWrt-Patch
A Patch for HiWiFi HC5661 OpenWrt

HiWiFi HC5661 OpenWrt编译补丁

HC5661-981213.patch 适用于：https://github.com/981213/openwrt

HC5661-wongsyrone.patch 适用于：https://github.com/wongsyrone/openwrt-1

HC5661-Barrier_Breaker.patch 适用于 Openwrt Barrier_Breaker

HC5661_chaos_calmer.patch 适用于 Openwrt Chaos Calmer

如打补丁失败，请对应修改。

HC5661.patch
默认管理地址：192.168.1.1:88
默认管理密码：admin

其他补丁：
默认管理地址：192.168.1.1
默认密码：无

# 使用方法：

上传到Openwrt根目录下

patch -p1 < HC5661.patch

make menuconfig

make V=99
