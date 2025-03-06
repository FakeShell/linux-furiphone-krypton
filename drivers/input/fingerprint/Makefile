#
# Makefile for all kinds of Fingerprint
#

obj-$(CONFIG_FT9362_FINGERPRINT_TEE) += focaltech_tee/

FINGERPRINT_LISTS := $(subst ",,$(CONFIG_MTK_FINGERPRINT_SUPPORT_LIST))
obj-y += $(foreach FINGERPRINT,$(FINGERPRINT_LISTS),$(FINGERPRINT)/)
