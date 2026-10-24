vendor := $(srctree)/$(src)

ifeq ($(CONFIG_NOTHING_IS_ASTEROIDS), y)
	ifneq "$(wildcard $(vendor)/qcom)" ""
		subdir-y += qcom
	endif
else ifeq ($(CONFIG_NOTHING_IS_FROGGER), y)
	ifneq "$(wildcard $(vendor)/qcom-frogger)" ""
		subdir-y += qcom-frogger
	endif
endif
