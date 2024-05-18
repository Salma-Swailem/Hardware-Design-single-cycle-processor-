# Single Cycle Processor Design

## Overview
This project involves the design and implementation of a single cycle processor. A single cycle processor is a type of CPU architecture where each instruction is completed in a single clock cycle. This makes it simpler to design and understand compared to multi-cycle or pipelined processors. This README provides an overview of the project, its structure, and instructions on how to set up and run the processor simulation.

## Table of Contents
1. [Features](#features)
2. [Requirements](#requirements)
3. [Setup and Installation](#setup-and-installation)

## Features
- **Single Cycle Execution**: Each instruction is executed in one clock cycle.
- **Basic Instructions**: Supports a fundamental set of instructions including arithmetic, logical, load/store, and control instructions.
- **Modular Design**: Components such as ALU, control unit, and memory are designed as separate modules for clarity and reuse.
- **Testbench**: A testbench is provided to verify the functionality of the processor.

## Requirements
- **Hardware Description Language**: Verilog
- **Simulation Tool**: ModelSim, Vivado, or any compatible Verilog simulator
- **Operating System**: Linux, macOS, or Windows
- **Memory**: Minimum 2GB RAM
- **Disk Space**: Minimum 500MB free space

## Setup and Installation
1. **Clone the Repository**:
   ```sh
   git clone https://github.com/Salma-Swailem/Hardware-Design-single-cycle-processor-.git
   cd single-cycle-processor 
