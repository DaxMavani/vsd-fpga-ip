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

## Work Completed for Task 1

### Step 1: Codespace Setup
- Forked and launched the official `vsd-riscv2` repository using GitHub Codespaces.
- Verified successful environment initialization.
- <img width="1595" height="810" alt="image" src="https://github.com/user-attachments/assets/f4e8c45c-0fe8-43dc-a751-350012a1a38f" />


### Step 2: RISC-V Reference Execution
- Compiled and executed the sample RISC-V program using:
  - `riscv64-unknown-elf-gcc`
  - `spike` ISA simulator
- Verified correct program output.

Sum 1 to 9 output

<img width="940" height="155" alt="sum_1_to_9" src="https://github.com/user-attachments/assets/a9a8ce53-475c-4f4d-9f32-b13d82d88973" />

now, using gcc

<img width="854" height="282" alt="gcc" src="https://github.com/user-attachments/assets/bd58bf8f-9e4b-4c19-a57e-b0647dfd1dbf" />

output using gcc

<img width="860" height="107" alt="gcc_out" src="https://github.com/user-attachments/assets/da63fba7-8b75-4f48-a4e9-a28f4115f99b" />

output using spike has also been verified

<img width="860" height="107" alt="gcc_out" src="https://github.com/user-attachments/assets/15ba6a52-f0a5-46b3-8e16-8ddb84a1a813" />

terminal novnc has been activated for a session

<img width="1016" height="147" alt="terminal_novnc" src="https://github.com/user-attachments/assets/314aca05-a38e-4f1f-9250-ac8f0f34e139" />


### Step 3: VSDFPGA Labs Execution
- Cloned `vsdfpga_labs` repository inside the same Codespace.
- Executed the `basicRISCV` lab:
  - Generated BRAM hex from firmware
  - Integrated firmware with RTL
  - Completed simulation-based build successfully
- No FPGA hardware tools were used.

the hex file has been seen in the output

<img width="912" height="357" alt="riscv_hex" src="https://github.com/user-attachments/assets/4aa5027c-fda5-4b4c-a535-b697a0e2f7a9" />




### Step 4: Local Environment Preparation
- Cloned both repositories locally using Git Bash.
- Reviewed the devcontainer Dockerfile to understand required toolchains and dependencies.
- FPGA synthesis and programming tools were intentionally not installed at this stage.

the repos have been cloned to local machine using git bash 

<img width="689" height="327" alt="local_clone" src="https://github.com/user-attachments/assets/c791642b-d686-4f8f-b99d-2ad4d2bb757d" />


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

