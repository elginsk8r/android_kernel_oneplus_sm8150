vendor := $(srctree)/$(src)

ifeq ($(CONFIG_OPLUS_SYSTEM_KERNEL_QCOM),y)
	ifneq "$(wildcard $(vendor)/oplus)" ""
		subdir-y += oplus
	endif
else
	ifneq "$(wildcard $(vendor)/qcom)" ""
		subdir-y += qcom
	endif
endif
