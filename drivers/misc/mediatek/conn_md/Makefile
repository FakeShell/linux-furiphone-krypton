#
# Copyright (C) 2015 MediaTek Inc.
#
# This program is free software: you can redistribute it and/or modify
# it under the terms of the GNU General Public License version 2 as
# published by the Free Software Foundation.
#
# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
# GNU General Public License for more details.
#

ccflags-y += -I$(srctree)/drivers/misc/mediatek/eccci/$(MTK_PLATFORM)
ccflags-y += -I$(srctree)/drivers/misc/mediatek/eccci/
ccflags-y += -I$(srctree)/drivers/misc/mediatek/dual_ccci/

ccflags-y += -I$(src)/include/

obj-$(CONFIG_MTK_CONN_MD) += conn_md_drv.o
conn_md_drv-objs := conn_md.o
conn_md_drv-objs += conn_md_exp.o
conn_md_drv-objs += conn_md_log.o
conn_md_drv-objs += conn_md_dump.o
conn_md_drv-objs += conn_md_dbg.o
conn_md_drv-objs += conn_md_test.o
