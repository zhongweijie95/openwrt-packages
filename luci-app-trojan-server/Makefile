# Copyright (C) 2019-2020 Lienol <lawlienol@gmail.com>
#
# This is free software, licensed under the GNU General Public License v3.
#

include $(TOPDIR)/rules.mk

PKG_NAME:=luci-app-trojan-server
LUCI_TITLE:=LuCI support for Trojan Server
LUCI_DEPENDS:=+luci-lib-jsonc +trojan 
LUCI_PKGARCH:=all

include ../../luci.mk

# call BuildPackage - OpenWrt buildroot signature