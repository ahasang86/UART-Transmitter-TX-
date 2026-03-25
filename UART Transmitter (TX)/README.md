# UART Transmitter (Verilog)

A fully functional UART transmitter supporting configurable baud rate and clock frequency. Implements start bit, 8 data bits, and stop bit. Includes a SystemVerilog testbench for simulation.

## Features
- Parameterized baud rate
- Clean state machine design
- Industry‑relevant communication protocol
- Ready for FPGA integration

## Files
- `design.sv` — UART TX module
- `testbench.sv` — Testbench with waveform‑friendly stimulus

## How to Run
Use EDAPlayground, ModelSim, or any SystemVerilog simulator. Set `testbench.sv` as the top module.
