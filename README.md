# Educational 8-bit CPU / SoC

<p align="center">
  <img src="images/breadboard_pcb.PNG" alt="breadboard pcb " width="10000"/>
</p>

---

## Project Overview

Alongside my undergraduate studies in Electrical & Electronic Engineering at Ulster University, I designed and built a simple 8-bit CPU using discrete TTL ICs on breadboards. What started as an electronics project quickly became a deep interest in computer architecture CPU hardware. Now at the end of my PhD, I revisited the project in my free time and created an improved SoC-based version on PCBs. This updated design will be provided to Ulster University so that other students can interact with and learn how CPUs work. An FPGA implementation and Python simulator of the CPU/SoC will also be shared here soon.

At a time when Artificial Intelligence is becoming mainstream, understanding computer hardware is more important than ever. The goal of this repo is to provide a learning CPU/SoC platform that others can use.

This repository will host the complete open-source project including:

🔨 Schematics, PCB and Gerber files.

🐍 A custom Python assembler.

🖥️ A Python-based CPU emulator/simulator for replicating without the hardware.

💻 An FPGA implementation of the CPU/SoC.

📚 Documentation.

🧩 Example programs and tutorials.

---

## CPU / SoC Features

- **Variable clock speeds. Programs can be run in two modes:**
  - Single-step mode – step-by-step execution with a push button.
  - Auto mode – run continuously with either a variable 555 timer clock (~1 Hz to 1 kHz) or a fixed 1 MHz oscillator.
- **Two programming modes:**
  - Manually with DIP switches to select memory address and instructions / data.
  - Automatically with an Arduino Nano and shift registers.
- **1kB total system memory (dual port SRAM IC):**
  - 256 byte program memory.
  - 256 byte data memory.
  - 256 byte stack memory.
  - 256 byte UART buffer memory.
- **4 general purpose registers:**
  - r0, r1, r2 and the accumulator.
- **5 special purpose registers:**
  - Memory Address register (MAR).
  - Program Counter (PC).
  - Stack Pointer (SP).
  - Instruction register (IR).
  - Flag register (FLAG).
- **8-bit ALU with dedicated register (RALU) capable of the following operations:**
  - Add / subtract.
  - AND / OR / NOT / XOR.
  - Shift left / right (logical).
  - Shift right (arithmetic).
  - Increment / decrement.
  - Generates Carry (CF), Zero (ZF), Negative (NF) and Overflow (OVF) flags
- **Micro-coded control unit (CU) with 3 EEPROMs**.
  - Up to 8 micro-steps per instruction.
- **Instruction-Set-Architecture (ISA):**
  - Load.
  - Store.
  - Move.
  - Arithmetic operations.
  - In 
- **Shared 8-bit data/address bus.**
- ****
- **Supported addressing modes:**
  - ??.
  - ??.
- **SoC Peripherals:**
  - A peripheral enable register (PER_EN).
  - A 4-digit, seven segment display register that can be configured as unsigned or signed representation (two's complement).
  - An LCD display with dedicated read / write instructions.
  - A UART at 19,200 baud rate, with status read and receive interrupt.
  - A configurable 8-bit timer with 8-bit clock prescaler register, with count read and zero / compare interrupts.
  - GPIO - 4 input registers (up to 32-bits) and 4 output registers (up to 32-bits).
- **4 CPU Interrupts (rising edge trigger):**
  - 2 external.
  - 1 UART.
  - 1 timer.
- **LEDs on all registers and combinatory logic to show the key states of the CPU at all times**.

---

## Architecture

### CPU

### SoC

---

## Builds

---

## Getting Started

---

## Ongoing Work

---
