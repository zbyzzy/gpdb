subdir=src/backend/replication
top_builddir=../../../..
include $(top_builddir)/src/Makefile.global

TARGETS=gp_replication

include $(top_srcdir)/src/backend/mock.mk

gp_replication.t: \
    $(MOCK_DIR)/backend/utils/error/assert_mock.o \
    $(MOCK_DIR)/backend/utils/error/elog_mock.o \
	$(MOCK_DIR)/backend/utils/misc/guc_gp_mock.o \
    $(MOCK_DIR)/backend/storage/lmgr/lwlock_mock.o \
	$(MOCK_DIR)/backend/storage/ipc/shmqueue_mock.o
