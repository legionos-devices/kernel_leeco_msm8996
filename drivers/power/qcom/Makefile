# Disable void-pointer-to-enum-cast
ifeq ($(cc-name),clang)
EXTRA_CFLAGS += $(call cc-disable-warning, void-pointer-to-enum-cast)
endif

obj-$(CONFIG_MSM_PM)		+= msm-pm.o pm-data.o
obj-$(CONFIG_MSM_IDLE_STATS)	+= lpm-stats.o
obj-$(CONFIG_MSM_NOPM)		+= no-pm.o
obj-$(CONFIG_PM)                += pm-boot.o
obj-$(CONFIG_APSS_CORE_EA)	+= msm-core.o debug_core.o
obj-$(CONFIG_MSM_APM)		+= apm.o
