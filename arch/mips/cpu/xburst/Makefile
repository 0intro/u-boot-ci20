#
# (C) Copyright 2000-2006
# Wolfgang Denk, DENX Software Engineering, wd@denx.de.
#
# SPDX-License-Identifier:	GPL-2.0+
#

extra-y	:= start.o
obj-y	+= cpu.o

obj-$(if $(filter jz4740,$(SOC)),y) += jz4740/
obj-$(if $(filter jz4780,$(SOC)),y) += jz4780/
