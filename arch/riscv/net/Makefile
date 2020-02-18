# SPDX-License-Identifier: GPL-2.0-only

ifeq ($(CONFIG_ARCH_RV64I),y)
	obj-$(CONFIG_BPF_JIT) += bpf_jit_comp.o
else
	obj-$(CONFIG_BPF_JIT) += bpf_jit_comp32.o
endif
