# Dockerfile Observations – Local Environment Preparation

## Identified Toolchains
- RISC-V GCC toolchain for cross-compilation
- GNU Make for build automation
- Python for scripts and tooling

## Simulation Tools
- Icarus Verilog for RTL simulation

## Notably Absent Tools
- Yosys
- nextpnr
- FPGA programmers

## Observation
The Dockerfile is intended as a reference for required tools and dependencies.
FPGA synthesis and hardware bring-up are intentionally deferred to later tasks.
