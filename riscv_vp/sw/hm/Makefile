OBJECTS  = main.o bootstrap.o irq.o
CFLAGS   = -march=rv32ima -mabi=ilp32
LDFLAGS  = -nostartfiles -Wl,--no-relax

# VP       = ~/risc-v/riscv-vp/vp/build/bin/riscv-vp-acc-hm # Change this to your riscv-vp path, or use
VP       = ../../build/bin/riscv-vp-acc-hm
VP_FLAGS = --intercept-syscalls --error-on-zero-traphandler=true 

include ../Makefile.common
