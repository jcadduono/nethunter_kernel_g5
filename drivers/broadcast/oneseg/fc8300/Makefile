#
# Makefile for the ISDB-Tmm FC8300 drivers.
#

# Each configuration option enables a list of files.
# LGE

obj-$(CONFIG_LGE_BROADCAST_ISDBT_JAPAN_FC8300)		+= broadcast_fc8300_drv_if.o
obj-$(CONFIG_LGE_BROADCAST_ISDBT_JAPAN_FC8300)		+= broadcast_fc8300.o
obj-$(CONFIG_LGE_BROADCAST_ISDBT_JAPAN_FC8300)		+= fc8300Driver/
EXTRA_CFLAGS += -Idrivers/broadcast/oneseg
EXTRA_CFLAGS += -Idrivers/broadcast/oneseg/fc8300/fc8300Driver/inc

