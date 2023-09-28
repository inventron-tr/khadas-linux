# SPDX-License-Identifier: GPL-2.0 OR BSD-3-Clause

obj-$(CONFIG_RTW88_CORE)	+= rtw88.o
rtw88-y += main.o \
	   mac80211.o \
	   util.o \
	   debug.o \
	   tx.o \
	   rx.o \
	   mac.o \
	   phy.o \
	   coex.o \
	   efuse.o \
	   fw.o \
	   ps.o \
	   sec.o \
	   wow.o \
	   bf.o \
	   regd.o \
	   sar.o

rtw88-$(CONFIG_RTW88_8822BE)	+= rtw8822b.o rtw8822b_table.o
rtw88-$(CONFIG_RTW88_8822CE)	+= rtw8822c.o rtw8822c_table.o

obj-$(CONFIG_RTW88_PCI)		+= rtwpci.o
rtwpci-objs			:= pci.o

obj-$(CONFIG_RTW88_8821CS)	+= rtw88_8821cs.o
rtw88_8821cs-objs		:= rtw8821cs.o

obj-$(CONFIG_RTW88_SDIO)	+= rtw88_sdio.o
rtw88_sdio-objs			:= sdio.o

obj-$(CONFIG_RTW88_8821C)	+= rtw88_8821c.o
rtw88_8821c-objs		:= rtw8821c.o rtw8821c_table.o
