# VSD FPGA Program – Task 1 Submission

## Task Title
Environment Setup & RISC-V Reference Bring-Up

## Objective
To set up a clean development environment, validate a working RISC-V reference flow, and execute simulation-based FPGA labs as a preparation step for upcoming RTL and FPGA integration tasks.

---

## Environment Used
- GitHub Codespace (primary)
- Git Bash on Windows (local preparation)

---

## Work Completed

### Step 1: Codespace Setup
- Forked and launched the official `vsd-riscv2` repository using GitHub Codespaces.
- Verified successful environment initialization.

### Step 2: RISC-V Reference Execution
- Compiled and executed the sample RISC-V program using:
  - `riscv64-unknown-elf-gcc`
  - `spike` ISA simulator
- Verified correct program output.

### Step 3: VSDFPGA Labs Execution
- Cloned `vsdfpga_labs` repository inside the same Codespace.
- Executed the `basicRISCV` lab:
  - Generated BRAM hex from firmware
  - Integrated firmware with RTL
  - Completed simulation-based build successfully
- No FPGA hardware tools were used.

### Step 4: Local Environment Preparation
- Cloned both repositories locally using Git Bash.
- Reviewed the devcontainer Dockerfile to understand required toolchains and dependencies.
- FPGA synthesis and programming tools were intentionally not installed at this stage.

---

## Reference Repositories
- RISC-V Reference: https://github.com/vsdip/vsd-riscv2
- FPGA Labs: https://github.com/vsdip/vsdfpga_labs

---

## Proof of Execution
Screenshots and logs are available in the `screenshots/` directory.

---

## Notes
This task was completed following an industry-style workflow emphasizing environment stability, reference validation, and understanding before modification.

