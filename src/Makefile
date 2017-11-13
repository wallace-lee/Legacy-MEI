# SPDX-License-Identifier: GPL-2.0
#
# Makefile - Intel Management Engine Interface (Intel MEI) Linux driver
# Copyright (c) 2010-2014, Intel Corporation.
#
EXTRA_CFLAGS += -DCONFIG_INTEL_MEI -DCONFIG_INTEL_MEI_ME

obj-m += mei.o
mei-objs := init.o
mei-objs += hbm.o
mei-objs += interrupt.o
mei-objs += client.o
mei-objs += main.o
mei-objs += bus.o
mei-objs += bus-fixup.o
#mei-objs += debugfs.o
#mei-$(CONFIG_DEBUG_FS) += debugfs.o

obj-m += mei-me.o
mei-me-objs := pci-me.o
mei-me-objs += hw-me.o

#obj-$(CONFIG_INTEL_MEI_TXE) += mei-txe.o
#mei-txe-objs := pci-txe.o
#mei-txe-objs += hw-txe.o

#mei-$(CONFIG_EVENT_TRACING) += mei-trace.o
#CFLAGS_mei-trace.o = -I$(src)
