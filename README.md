# Single-Cycle-RiscV-Architecture

This project showcases the implementation of a RISC-V processor using a single-cycle architecture. Each instruction is executed in a single clock cycle, and the design incorporates Control and Status Registers (CSR) for effective system-level control and exception handling. The CSR trap mechanism is hard-wired to manage exceptions seamlessly.

# Prerequisites

To set up and work on this project, the following tools and libraries are required:
# SystemVerilog: 
For designing and implementing the processor.
# VSCode: 
Recommended for editing and managing the SystemVerilog files.
# GTKWave: 
For waveform visualization (requires Multisim for functionality).
# Simulator: 
Tools like ModelSim or Vivado for simulation and testing.

# Commands To use 
```
vlog *.sv
vsim -c tb_processor -voptargs=+acc -do "run -all"
gtkwave processor.vcd
```

