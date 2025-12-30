# 🕹️ CHIP-8 Virtual CPU Emulator

A minimalist, low-level emulation of the 1970s CHIP-8 virtual machine. This project focuses on replicating the core CPU architecture, memory management, and instruction set of a classic game console using the C programming language.

---

## 🚀 Project Overview

This emulator acts as a "software-defined computer." It replicates the internal hardware of a vintage system, allowing a modern PC to interpret and execute 16-bit CHIP-8 opcodes.

### 🧠 Hardware Specifications
* **Memory (RAM)**: 4,096 bytes (4KB) of addressable space.
* **Registers**: 16 general-purpose 8-bit registers (labeled V0 through VF).
* **Program Counter (PC)**: Tracks execution flow, starting at memory address `0x200`.
* **Instruction Set**: A custom "Fetch-Decode-Execute" loop that processes hexadecimal opcodes.

---

## 📂 Project Structure

```text
CHIP8-Emulator/
├── src/
│   └── main.c      # The CPU logic and instruction handler
├── README.md       # Project documentation
└── .gitignore      # Configuration to keep the repository clean
