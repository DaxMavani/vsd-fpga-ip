# Understanding Check – Task 1

## 1. Where is the RISC-V program located?
The RISC-V programs are located in the samples/ directory of the vsd-riscv2 repository.

## 2. How is the program compiled and loaded into memory?
The program is cross-compiled using the RISC-V GNU toolchain (riscv64-unknown-elf-gcc) to produce a RISC-V ELF binary.
This ELF binary is then executed using the Spike RISC-V ISA simulator

## 3. How does the RISC-V core access memory and MMIO?
The RISC-V core accesses memory and memory-mapped I/O using standard load and store instructions.
Both main memory and peripherals are mapped into a single address space, and specific address ranges correspond to RAM or memory-mapped registers.

## 4. Where would a new FPGA IP block integrate in this system?
A new FPGA IP block would integrate on the system interconnect (bus) and be assigned a dedicated memory-mapped address range.
The IP would be connected alongside existing peripherals, and address decoding logic would route accesses from the RISC-V core to the new IP.
Software would interact with the IP by performing load and store operations to its assigned memory-mapped registers.
