################################################
#
# xf86vidmodeproto
#
################################################
PK_XF86VIDMODEPROTO_NAME        := xf86vidmodeproto
PK_XF86VIDMODEPROTO_VERSION     := $(CONFIG_PK_XF86VIDMODEPROTO_VERSION)
PK_XF86VIDMODEPROTO_SITE        := $(CONFIG_PK_XF86VIDMODEPROTO_URL)
PK_XF86VIDMODEPROTO_GITHUB      := $(CONFIG_PK_XF86VIDMODEPROTO_GITHUB)
PK_XF86VIDMODEPROTO_SUBNAME     :=
PK_XF86VIDMODEPROTO_BUILDARCH   := $(CONFIG_PK_XF86VIDMODEPROTO_BUILDARCH)
PK_XF86VIDMODEPROTO_DIR         := $(srctree)/package/xf86vidmodeproto
PK_XF86VIDMODEPROTO_PATCH       := $(PK_XF86VIDMODEPROTO_DIR)/patch
PK_XF86VIDMODEPROTO_BSBIT       := xf86vidmodeproto-$(PK_XF86VIDMODEPROTO_VERSION).bsbit
PK_XF86VIDMODEPROTO_OUT         :=
PK_XF86VIDMODEPROTO_SCRIPTS     := $(srctree)/scripts/package/package.sh
PK_XF86VIDMODEPROTO_TAR         := $(CONFIG_PK_XF86VIDMODEPROTO_TAR)
PK_XF86VIDMODEPROTO_PACKAGE     :=
PK_XF86VIDMODEPROTO_CONFIG      := $(CONFIG_PK_XF86VIDMODEPROTO_CONFIG)
SUB_TARGET              	+= $(PK_XF86VIDMODEPROTO_DIR)/build

PK_XF86VIDMODEPROTO_sh = $(CONFIG_SHELL) $(PK_XF86VIDMODEPROTO_SCRIPTS) \
                 $1X \
                 $(PK_XF86VIDMODEPROTO_NAME)X \
                 $(PK_XF86VIDMODEPROTO_VERSION)X \
                 $(PK_XF86VIDMODEPROTO_SITE)X \
                 $(PK_XF86VIDMODEPROTO_GITHUB)X \
                 $(PK_XF86VIDMODEPROTO_PATCH)X \
                 $(CONFIG_LINUX_KERNEL_VERSION)X \
	         $(CONFIG_MAIN_PROJ_NAME)X \
                 $(PK_XF86VIDMODEPROTO_TAR)X \
                 $(CONFIG_LINUX_KERNEL_CROSS_COMPILE)X \
                 $(PK_XF86VIDMODEPROTO_SUBNAME)X \
                 $(CONFIG_PK_XF86VIDMODEPROTO_CONFIG)X \
                 $(CONFIG_PK_XF86VIDMODEPROTO_LIBPATH)X \
                 $(CONFIG_PK_XF86VIDMODEPROTO_CPPFLAGS)X \
                 $(CONFIG_PK_XF86VIDMODEPROTO_DPKCONFIG)X \
                 $(CONFIG_PK_XF86VIDMODEPROTO_CFLAGS)X \
                 $(CONFIG_PK_XF86VIDMODEPROTO_LDFLAGS)X \
                 $(CONFIG_PK_XF86VIDMODEPROTO_CXXFLAGS)X \
                 $(CONFIG_PK_XF86VIDMODEPROTO_ASFLAGS)X \
                 $(PK_XF86VIDMODEPROTO_BSBIT)X \
                 $(PK_XF86VIDMODEPROTO_BUILDARCH)X

$(PK_XF86VIDMODEPROTO_DIR)/build: FORCE
	$(Q)$(call PK_XF86VIDMODEPROTO_sh,$(srctree))
