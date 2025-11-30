## 🛠️ Essential Reverse Engineering Tools

### **Cross-Platform Disassemblers/Decompilers**
- **Ghidra** - NSA's open-source reverse engineering suite (FREE)
- **IDA Pro** - Industry standard disassembler (Commercial)
- **Binary Ninja** - Modern reverse engineering platform (Commercial)
- **Radare2** - Unix-like reverse engineering framework (FREE)
- **Cutter** - GUI for Radare2 (FREE)

### **Debuggers**
- **GDB** (GNU Debugger) with enhancements:
  - **GEF** (GDB Enhanced Features)
  - **Pwndbg**
  - **Pedra**
- **x64dbg** - Windows debugger (FREE)
- **OllyDbg** - Windows debugger (FREE)
- **WinDbg** - Microsoft debugger

### **Binary Analysis Tools**
- **objdump** - Binary object analysis
- **readelf** - ELF file analysis
- **ltrace/strace** - Library/system call tracing
- **file** - File type identification
- **strings** - Extract strings from binaries
- **hexdump/xxd** - Hex viewing

## 📱 Platform-Specific Tools

### **PE (Windows) Analysis**
- **PE-bear** - PE file analyzer
- **CFF Explorer** - PE editor
- **PEiD** - PE packer detection
- **Resource Hacker** - Resource editor

### **.NET Analysis**
- **dnSpy** - .NET debugger and assembly editor
- **ILSpy** - .NET decompiler
- **dotPeek** - JetBrains .NET decompiler

### **Android (APK) Analysis**
- **Jadx** - Dex to Java decompiler
- **APKTool** - Reverse engineering APK files
- **Bytecode Viewer** - Java/Android bytecode analysis
- **Frida** - Dynamic instrumentation toolkit
- **Objection** - Runtime mobile exploration

### **Mobile & Game Platforms**
- **Godot** - For Godot game engine analysis
- **Unity** tools for Unity game analysis
- **Switch homebrew tools** for NRO files

### **WebAssembly (WASM)**
- **wasm2wat/wat2wasm** - WebAssembly text format
- **wasm-decompile** - WASM decompilation
- **Browser DevTools** - For client-side analysis

## 🔧 Specialized Tools

### **Python Bytecode (PYC)**
- **uncompyle6** - Python bytecode decompiler
- **pycdc** - Python decompiler
- **dis** - Python disassembler module

### **Lua Bytecode**
- **luadec** - Lua decompiler
- **unluac** - Lua decompiler

### **Java Bytecode**
- **JD-GUI** - Java decompiler
- **Procyon** - Java decompiler
- **CFR** - Another Java decompiler

### **Game Boy**
- **BGB** - Game Boy emulator/debugger
- **No$GMB** - Game Boy debugger

### **EVM (Ethereum)**
- **evm-dis** - Ethereum VM disassembler
- **Panoramix** - EVM decompiler

### **PowerShell**
- **PowerShell ISE** - Built-in PowerShell editor
- **Various deobfuscation scripts**

## 🎯 Challenge-Specific Tools

### **For Packed Binaries**
- **upx** - Ultimate Packer for eXecutables (also unpacks)
- **Detect It Easy** - Packer/compiler detection

### **For Anti-Debugging Challenges**
- **ScyllaHide** - Advanced ring 0 anti-anti-debug plugin

### **For Automation Scripting**
- **Python** with:
  - **pwntools** - CTF framework
  - **angr** - Binary analysis platform
  - **z3-solver** - Theorem prover
  - **capstone** - Disassembly framework
  - **keystone** - Assembler framework

## 📚 Learning Resources

### **Assembly Languages to Learn**
- **x86/x64** - Most common in challenges
- **ARM** - For mobile and embedded
- **MIPS** - Occasionally appears

### **Practice Platforms**
- **Crackmes.one** - Practice crackmes
- **Beginners RE** - Guided reverse engineering
- **Microcorruption** - Embedded security CTF

### **Useful Websites**
- **shell-storm.org** - Shellcode and RE resources
- **opensecuritytraining.info** - Free security training