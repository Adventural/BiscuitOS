################################################
#
# PCP linux 2.6.12.5
#
################################################
PK_PCP_2_6_12_5_NAME        := BiscuitOS_PCP
PK_PCP_2_6_12_5_VERSION     := $(CONFIG_PK_PCP_2_6_12_5_VERSION)
PK_PCP_2_6_12_5_SITE        := $(CONFIG_PK_PCP_2_6_12_5_URL)
PK_PCP_2_6_12_5_GITHUB      := $(CONFIG_PK_PCP_2_6_12_5_GITHUB)
PK_PCP_2_6_12_5_SUBNAME     :=
PK_PCP_2_6_12_5_BUILDARCH   := $(CONFIG_PK_PCP_2_6_12_5_BUILDARCH)
PK_PCP_2_6_12_5_DIR         := $(srctree)/package/memory_history/PCP/linux-2.6.12.5
PK_PCP_2_6_12_5_PATCH       := $(PK_PCP_2_6_12_5_DIR)/patch
PK_PCP_2_6_12_5_BSBIT       := BiscuitOS_PCP-$(PK_PCP_2_6_12_5_VERSION).bsbit
PK_PCP_2_6_12_5_OUT         :=
PK_PCP_2_6_12_5_SCRIPTS     := $(srctree)/scripts/package/package-memory.sh
PK_PCP_2_6_12_5_TAR         := $(CONFIG_PK_PCP_2_6_12_5_TAR)
PK_PCP_2_6_12_5_PACKAGE     :=
PK_PCP_2_6_12_5_CONFIG      := $(CONFIG_PK_PCP_2_6_12_5_CONFIG)
SUB_TARGET                  += $(PK_PCP_2_6_12_5_DIR)/build

PK_PCP_2_6_12_5_sh = $(CONFIG_SHELL) $(PK_PCP_2_6_12_5_SCRIPTS) \
                 $1X \
                 $(PK_PCP_2_6_12_5_NAME)X \
                 $(PK_PCP_2_6_12_5_VERSION)X \
                 $(PK_PCP_2_6_12_5_SITE)X \
                 $(PK_PCP_2_6_12_5_GITHUB)X \
                 $(PK_PCP_2_6_12_5_PATCH)X \
                 $(CONFIG_LINUX_KERNEL_VERSION)X \
	         $(CONFIG_MAIN_PROJ_NAME)X \
                 $(PK_PCP_2_6_12_5_TAR)X \
                 $(CONFIG_LINUX_KERNEL_CROSS_COMPILE)X \
                 $(PK_PCP_2_6_12_5_SUBNAME)X \
                 $(CONFIG_PK_PCP_2_6_12_5_CONFIG)X \
                 $(CONFIG_PK_PCP_2_6_12_5_LIBPATH)X \
                 $(CONFIG_PK_PCP_2_6_12_5_CPPFLAGS)X \
                 $(CONFIG_PK_PCP_2_6_12_5_DPKCONFIG)X \
                 $(CONFIG_PK_PCP_2_6_12_5_CFLAGS)X \
                 $(CONFIG_PK_PCP_2_6_12_5_LDFLAGS)X \
                 $(CONFIG_PK_PCP_2_6_12_5_CXXFLAGS)X \
                 $(CONFIG_PK_PCP_2_6_12_5_ASFLAGS)X \
                 $(PK_PCP_2_6_12_5_BSBIT)X \
                 $(PK_PCP_2_6_12_5_BUILDARCH)X \
		 $(PK_PCP_2_6_12_5_CSRCFILE)X \
                 $(CONFIG_PK_PCP_2_6_12_5_SRCFILE)X \
                 $(CONFIG_PK_PCP_2_6_12_5_CSRCFILE)

$(PK_PCP_2_6_12_5_DIR)/build: FORCE
	$(Q)$(call PK_PCP_2_6_12_5_sh,$(srctree))
