ifeq ($(CONFIG_MACH_XIAOMI_UGG_TREBLE),y)
dtb-$(CONFIG_MACH_XIAOMI_UGG_TREBLE) += msm8940-pmi8937-mtp-treble.dtb
else
dtb-$(CONFIG_MACH_XIAOMI_UGG) += msm8940-pmi8937-mtp-treble.dtb
endif

ifeq ($(CONFIG_MACH_XIAOMI_UGGLITE_TREBLE),y)
dtb-$(CONFIG_MACH_XIAOMI_UGGLITE_TREBLE) += ugglite-full.dtb
else
dtb-$(CONFIG_MACH_XIAOMI_UGGLITE) += msm8917-pmi8937-mtp.dtb
endif

always		:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files	:= *.dtb
