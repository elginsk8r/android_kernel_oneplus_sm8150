#
# Makefile for the touchscreen drivers.
#
subdir-ccflags-$(CONFIG_TOUCHPANEL_MTK_PLATFORM) += -I$(srctree)/drivers/misc/mediatek/include/

obj-$(CONFIG_TOUCHPANEL_OPLUS) += util_interface/
obj-$(CONFIG_TOUCHPANEL_OPLUS) += touchpanel_common_driver.o touchpanel_healthinfo.o touchpanel_exception.o
obj-$(CONFIG_TOUCHPANEL_SYNAPTICS) += Synaptics/
obj-$(CONFIG_TOUCHPANEL_SAMSUNG) += Samsung/
