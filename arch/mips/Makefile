#
# SPDX-License-Identifier:	GPL-2.0+
#

ifeq (,$(filter $(SOC), jz))
head-y := arch/mips/cpu/xburst/start.o
libs-y += arch/mips/cpu/xburst/
else
head-y := arch/mips/cpu/$(CPU)/start.o
libs-y += arch/mips/cpu/
endif

libs-y += arch/mips/lib/

libs-$(CONFIG_SOC_AU1X00) += arch/mips/mach-au1x00/
