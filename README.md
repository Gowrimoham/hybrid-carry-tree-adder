# Hybrid Carry Tree Adder

## Overview

This project presents the design and evaluation of a Hybrid Carry Tree Adder combining Brent-Kung and Han-Carlson parallel prefix architectures.

The objective is to achieve a balance between:

- Low propagation delay
- Reduced area utilization
- Lower routing complexity

## Features

- Verilog HDL implementation
- 8-bit, 16-bit and 32-bit architectures
- Brent-Kung Adder
- Han-Carlson Adder
- Hybrid Carry Tree Adder
- FPGA implementation using Xilinx Vivado

## Results

| Architecture | Delay (ns) | Slices |
|-------------|-----------|---------|
| BKA-32 | 34.45 | 66 |
| HCA-32 | 35.88 | 72 |
| Hybrid-32 | 34.74 | 60 |

## Tools Used

- Verilog HDL
- Xilinx Vivado 2024.1
- FPGA Design
- Digital Design

## Author

Nanda
