extra-$(CONFIG_GENERIC_LINKER_SCRIPT) += barebox.lds
obj-$(CONFIG_CSRC_R4K_LIB) += csrc-r4k.o
obj-y += lshrdi3.o
obj-y += ashldi3.o
obj-y += ashrdi3.o
obj-y += memory.o
obj-y += cpu-probe.o

obj-$(CONFIG_CPU_MIPS32) += c-r4k.o
obj-$(CONFIG_CPU_MIPS64) += c-r4k.o

obj-$(CONFIG_CMD_MIPS_CPUINFO) += cpuinfo.o
obj-$(CONFIG_CMD_BOOTM)	+= bootm.o
