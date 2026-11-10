custom, bare-metal operating system designed specifically for penetration testing and cybersecurity research.
Features
 Minimalist architecture for direct hardware control.
 Custom security tooling integration.
 Optimized for live-boot environments and virtual machines.
Getting Started
Prerequisites
 A cross-compiler toolchain (x86_64-elf).
 QEMU or a virtual machine manager for testing.
Building
1. Clone the repository.
2. Run ⁠make⁠ to compile the kernel.
3. Use the build script to generate the bootable ISO.
Usage
Boot the generated ISO in your preferred virtual machine or flash it to a USB drive for live testing.
