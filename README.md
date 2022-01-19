# RT-AC1200GU-OpenWrt
基于lean的OpenWrt源码改动而来，请使用lean源码。
使用方法：
将mt7621_asus_rt-ac1200gu.dts复制到lede\target\linux\ramips\dts
将mt7621.mk覆盖lede\target\linux\ramips\image中的mt7621.mk
使用make menuconfig，在机型选择中
Target System 选择 MediaTek Ralink MIPS
Subtarget 选择 MT7621 based boards
Target Profile 选择RT-AC1200GU即可
