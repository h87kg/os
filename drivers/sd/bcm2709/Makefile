################################################################################
#
#   Copyright (c) 2014 Minoca Corp. All rights reserved.
#
#   Module Name:
#
#       SD BCM2709
#
#   Abstract:
#
#       This module implements the BCM2709 SD controller driver.
#
#   Author:
#
#       Chris Stevens 10-Dec-2014
#
#   Environment:
#
#       Kernel
#
################################################################################

BINARY = sdbm2709.drv

BINARYTYPE = so

BINPLACE = bin

OBJS = emmc.o       \
       sdbm2709.o   \

DYNLIBS = $(BINROOT)/kernel             \
          $(BINROOT)/sd.drv             \

include $(SRCROOT)/os/minoca.mk

