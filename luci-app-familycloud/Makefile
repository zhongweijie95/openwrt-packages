# Copyright (C) 2016 Openwrt.org
#
# This is free software, licensed under the Apache License, Version 2.0 .
#

include $(TOPDIR)/rules.mk

LUCI_TITLE:=LuCI support for FamilyCloudSpeeder
LUCI_DEPENDS:=+coreutils +coreutils-nohup +libreadline +libcurl +libopenssl +bash +curl +wget-ssl +openssl-util +ca-certificates +ca-bundle
LUCI_PKGARCH:=all
PKG_NAME:=luci-app-familycloud

include ../../luci.mk

# call BuildPackage - OpenWrt buildroot signature

