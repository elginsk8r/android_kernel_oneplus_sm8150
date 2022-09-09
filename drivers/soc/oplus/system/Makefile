# SPDX-License-Identifier: GPL-2.0-only
# Copyright (C) 2018-2020 Oplus. All rights reserved.
#
# Makefile for the OPLUS Linux Kernel system team specific device drivers.
#

ifeq ($(CONFIG_KASAN),y)
subdir-ccflags-y += -Wno-format
endif

obj-y 	+= platform.o
obj-$(CONFIG_OPLUS_DEVICE_IFNO)	+=  device_info.o
obj-$(CONFIG_OPLUS_FEATURE_OPROJECT) += oplus_project.o
obj-$(CONFIG_OPLUS_FEATURE_PROJECTINFO)	+=  boot_mode.o

