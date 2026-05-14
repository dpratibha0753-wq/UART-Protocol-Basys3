# UART Communication using Verilog on FPGA

## Objective
To implement UART communication protocol using Verilog HDL on Basys3 FPGA.

## Features
- UART Transmission
- UART Reception
- Baud Rate Generator
- ASCII Processing
- Case Conversion

## Hardware Used
- Basys3 FPGA Board

## Software Used
- Xilinx Vivado
- Putty terminal

## Working
Data is transmitted from PC terminal to FPGA using UART.
The FPGA processes the received data and transmits modified data back to PC.

## Files Included
- UART_top.v
- uart_tx.v
- uart_rx.v
- baud_generator.v
- debounce.v
- basys3.xdc
- uart_tb.v

## Future Improvements
- FIFO Buffer
- Error Detection
- Configurable Baud Rate
