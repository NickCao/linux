# SPDX-License-Identifier: GPL-2.0
CFLAGS += -g -std=gnu99 $(KHDR_INCLUDES)
LDLIBS += -lcap

TEST_GEN_PROGS := clone3 clone3_clear_sighand clone3_set_tid \
	clone3_cap_checkpoint_restore

include ../lib.mk
