# SPDX-License-Identifier: GPL-3.0-only
#
# Copyright (C) 2019-2021 Tianling Shen <cnsztl@immortalwrt.org>

include $(TOPDIR)/rules.mk

LUCI_TITLE:=LuCI support for UnblockNeteaseMusic
LUCI_DEPENDS:=+busybox +dnsmasq-full +ipset +jsonfilter +node +uclient-fetch +ucode \
	@(PACKAGE_libustream-mbedtls||PACKAGE_libustream-openssl||PACKAGE_libustream-wolfssl)
LUCI_PKGARCH:=all

PKG_NAME:=luci-app-unblockneteasemusic

PKG_MAINTAINER:=Tianling Shen <cnsztl@immortalwrt.org>

include ../../luci.mk

# call BuildPackage - OpenWrt buildroot signature
