# Copyright (C) 2020 Silvan
include $(TOPDIR)/rules.mk

LUCI_TITLE:=LuCI support for UnblockNeteaseMusic-Go
LUCI_DEPENDS:=+bash +busybox +unzip +coreutils +coreutils-nohup +curl +dnsmasq-full +ipset +luci-compat +openssl-util +UnblockNeteaseMusic-Go
LUCI_PKGARCH:=all
PKG_NAME:=luci-app-unblockneteasemusic-go

PKG_MAINTAINER:=https://github.com/cnsilvan/luci-app-unblockneteasemusic

include ../../luci.mk

# call BuildPackage - OpenWrt buildroot signature
