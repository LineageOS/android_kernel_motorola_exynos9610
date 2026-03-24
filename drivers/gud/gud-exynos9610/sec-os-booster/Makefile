#
# Makefile for Secure OS booster API
#
obj-$(CONFIG_SECURE_OS_BOOSTER_API) += sec_os_booster.o

# MobiCore kernel driver path
GUD_ROOT_FOLDER := drivers/gud/gud-exynos9610

ccflags-y += -I $(srctree)/include/soc/samsung/
# Includes MobiCore kernel driver
ccflags-y += -I$(GUD_ROOT_FOLDER)/MobiCoreDriver
ccflags-y += -I$(GUD_ROOT_FOLDER)/MobiCoreDriver/public
