# Description
这是一个兆能-m2固件编译仓库，只添加了我自己用的插件，无wifi和usb支持。

linux内核为6.6，原仓库请见workflow文件

插件如下
- luci-app-zerotier
- luci-app-passwall
- adguardhome
- luci-app-smartdns

# 展示固件

此为passwall+adguardhome+smartdns+zerotier四个插件一起运行的内存占用，没有超过512M，推荐512MB以上的zn-m2使用。

![pic](./pic/01.jpg)

如果只开passwall+zerotier占用大概200MB，内存很吃紧。图就懒得截了
