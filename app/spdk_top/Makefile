#  SPDX-License-Identifier: BSD-3-Clause
#  Copyright (c) Intel Corporation.
#  All rights reserved.
#

SPDK_ROOT_DIR := $(abspath $(CURDIR)/../..)
include $(SPDK_ROOT_DIR)/mk/spdk.common.mk

APP = spdk_top

C_SRCS := spdk_top.c

SPDK_LIB_LIST = rpc
LIBS=-lpanel -lmenu -lncurses

include $(SPDK_ROOT_DIR)/mk/spdk.app.mk
