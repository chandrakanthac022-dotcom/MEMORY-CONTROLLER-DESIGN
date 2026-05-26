# Memory Controller Design

## Overview
The Memory Controller is a digital hardware module responsible for managing communication between a processor/system bus and external memory devices. This project implements a configurable Memory Controller using Verilog/SystemVerilog to perform reliable and synchronized memory read/write operations.

The design is developed for FPGA/ASIC applications and demonstrates core digital design concepts including finite state machine (FSM) control, address decoding, timing management, and data handling.

---

## Objectives
- Design an efficient memory access controller
- Implement synchronized read and write operations
- Manage memory timing and control signals
- Provide scalable and modular RTL architecture
- Verify functionality through simulation

---

## Key Features
- Synchronous Read/Write Operations
- FSM-Based Control Logic
- Address Decoding Mechanism
- Data Buffering Support
- Configurable Address and Data Width
- Timing and Control Signal Management
- Modular RTL Design
- FPGA Compatible Implementation

---

## System Architecture

         +----------------------+
                |      Processor       |
                +----------+-----------+
                           |
                           |
                +----------v-----------+
                |   Memory Controller  |
                |----------------------|
                |  Control Unit (FSM)  |
                |  Address Decoder     |
                |  Data Buffer         |
                +----------+-----------+
                           |
                           |
                +----------v-----------+
                |    External Memory   |
                +----------------------+
