# The Xiaomi "mihw" module lives outside this tree (vendor/xiaomi/...).
# Only descend into it when the sources are actually present.
mihw_dir := $(srctree)/../../../vendor/xiaomi/kernel_modules/mihw
ifneq ($(wildcard $(mihw_dir)/Makefile),)
obj-$(CONFIG_MILLET) += $(mihw_dir)/
endif
