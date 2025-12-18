# 64-bit CPU Design (Logisim)

A custom **64-bit processor** designed and implemented in **Logisim**, featuring a full 64-bit datapath, a multi-operation ALU, control logic, and a custom instruction format.

This project focuses on core computer architecture concepts including datapath design, control signaling, instruction decoding, and arithmetic/logic unit implementation.

## Overview

The processor is built from fundamental digital logic components and models the behavior of a simple 64-bit CPU.  
It includes a clocked execution model, a control unit, and a defined instruction format used to drive ALU operations and data movement.

## Architecture

- **64-bit datapath**
- **Clocked execution**
- **Control unit**
- **Custom instruction set**
- **Carry-out support**
- Instruction decoding and control signal generation

The CPU executes instructions using a **16-bit instruction format**, which is decoded by the control unit to drive ALU selection, data routing, and control flow.

## Arithmetic Logic Unit (ALU)

The 64-bit ALU supports the following operations:

- ADD (Adder)
- AND
- CLEAR
- COMPARE (Comparator)
- DECREMENT
- INCREMENT
- LEFT SHIFT
- RIGHT SHIFT
- NAND
- NOR
- NOT
- OR
- XNOR
- XOR

The ALU includes **carry-out** support and is fully integrated into the CPU datapath.

## Core Components

- **ALU**
  - Multi-operation 64-bit arithmetic and logic unit
- **Control Unit**
  - Decodes 16-bit instructions
  - Generates control signals for datapath and ALU
- **Clock**
  - Drives synchronous execution
- **Registers / Data Path**
  - 64-bit data handling and routing
- **Instruction Logic**
  - Instruction decoding and operation selection

## Tools Used

- **Logisim**
- Digital logic design
- Computer architecture principles
- Datapath and control modeling

## Purpose

This project demonstrates:
- Understanding of 64-bit datapath design
- ALU construction and operation selection
- Instruction decoding and control logic
- Clocked digital system design
- Low-level computer architecture concepts

## Notes

This CPU is an educational design intended to demonstrate architectural principles rather than a complete or optimized processor implementation.
