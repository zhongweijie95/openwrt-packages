# Copyright (C) 2020 Openwrt.org
#
# This is free software, licensed under the Apache License, Version 2.0 .
#
#

include $(TOPDIR)/rules.mk

PKG_NAME:=luci-app-unblockmusic

PKG_CONFIG_DEPENDS := \
	CONFIG_UnblockNeteaseMusic_Go \
	CONFIG_UnblockNeteaseMusic_NodeJS

include $(INCLUDE_DIR)/package.mk

define Package/$(PKG_NAME)/config
  source "$(SOURCE)/Config.in"
endef

PKG_LICENSE:=Apache-2.0

LUCI_TITLE:=LuCI support for Unblock NeteaseCloudMusic
LUCI_DEPENDS:=+dnsmasq-full +ipset +uclient-fetch +UnblockNeteaseMusic_NodeJS:UnblockNeteaseMusic +UnblockNeteaseMusic_Go:UnblockNeteaseMusic-Go
LUCI_PKGARCH:=all

PKG_MAINTAINER:=lean

include ../../luci.mk

# call BuildPackage - OpenWrt buildroot signature

