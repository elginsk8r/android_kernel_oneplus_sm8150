vendor := $(srctree)/$(src)

ifeq ($(CONFIG_OPLUS_FEATURE_OPROJECT),y)
	ifneq "$(wildcard $(vendor)/oplus)" ""
		subdir-y += oplus
	endif
else
	ifneq "$(wildcard $(vendor)/qcom)" ""
		subdir-y += qcom
	endif
endif
