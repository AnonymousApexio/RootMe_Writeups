## 🛠️ Essential Tools by Category

### **1. Debuggers & Disassemblers**
```yaml
# Primary Debugger
gdb (GNU Debugger)
- gdb-peda (Python Exploit Development Assistance)
- gdb-gef (GDB Enhanced Features)
- pwndbg (Modern GDB interface)

# Disassemblers & Decompilers
ghidra - NSA's reverse engineering suite
radare2 - Unix-like reverse engineering framework
cutter - GUI for radare2
IDA Pro - Interactive disassembler (commercial)
Binary Ninja - Reverse engineering platform
objdump - Binary analysis (built-in)
readelf - ELF file analysis
```

### **2. Binary Analysis Tools**
```yaml
# File identification
file - Identify file type
strings - Extract strings from binary

# Binary inspection
ltrace - Library call tracer
strace - System call tracer
ldd - List dynamic dependencies
nm - List symbols from object files

# Security features check
checksec - Check binary security features
patchelf - Modify ELF binaries
```

### **3. Exploitation Frameworks**
```yaml
# Python-based exploitation
pwntools - CTF framework & exploit development
angr - Binary analysis platform
ROPgadget - Find ROP gadgets
ROPER - ROP gadget finder
one_gadget - Find one-gadget RCE in libc

# Memory corruption
libc-database - Libc database for offsets
```

### **4. Architecture-Specific Tools**
```yaml
# x86/x64
gdb-multiarch - Multi-architecture GDB
qemu-x86_64 - x64 emulation
qemu-i386 - x86 emulation

# ARM
arm-linux-gnueabi-gdb - ARM debugging
qemu-arm - ARM emulation
arm_now - Quick ARM emulation setup

# MIPS
mips-linux-gnu-gdb - MIPS debugging
qemu-mips - MIPS emulation

# RISC-V
riscv64-linux-gnu-gdb - RISC-V debugging
qemu-riscv64 - RISC-V emulation
```

### **5. Heap Exploitation Tools**
```yaml
# Heap analysis
heap-viewer - Visualize heap layout
villoc - Heap visualization
heapwn - Heap exploitation helper

# Modern heap
pwninit - Auto setup for pwn challenges
gef-heap - Heap commands for GEF
```

### **6. Kernel Exploitation
```yaml
# Kernel debugging
kgdb - Kernel debugger
qemu-system-* - Full system emulation

# Kernel modules
insmod/modprobe - Load kernel modules
dmesg - Kernel message buffer
```