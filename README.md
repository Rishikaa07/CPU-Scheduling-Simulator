# 8-Bit CPU Simulator
A custom-designed 8-bit CPU simulation built using CircuitVerse, complete with a control unit, ALU, instruction set, memory interface, and microinstruction logic. This project simulates a basic Von Neumann architecture processor capable of executing a variety of low-level instructions.

## Author: Rishika Verma


## 🔗 CircuitVerse Project
You can explore and run the processor simulation here:<br>
👉<a href="https://circuitverse.org/users/315732/projects/cpu-scheduling-simulator"> CPU ALU Scheduling Simulator on CircuitVerse</a>




### 📁 How to Use the .cv File
<b>To import and use the project locally on CircuitVerse:<br></b>
1. Visit the <a href="https://circuitverse.org/">CircuitVerse Simulator.</a><br>
2. Click on Launch Simulator.<br>
3. Go to the Projects section.<br>
4. Click Import file.<br>
5. Upload the .cv file from your system<br>
6. Click Upload.<br>
7. Your circuit will be available to edit, simulate, and analyze.<br>

## 🧠 Project Features

### 🏗️ Main Components:
- **General CPU Register**: 8-bit registers for temporary data storage.
- **Program Counter (PC)**: Manages the instruction sequence.
- **Memory Unit (EEPROM)**: ROM-based instruction/data storage.
- **Memory Address Register (MAR)**: Holds the address for memory access.
- **Instruction Register & Decoder**: Fetches and decodes instructions.
- **Arithmetic and Logic Unit (ALU)**: Supports ADD, SUB, LSHIFT, RSHIFT.
- **Status Register**: Provides condition flags for jumps.
- **Control Processor**: Generates control words using EEPROM and a ring counter.

---

## 🛠️ Supported Instructions

The instruction set supports the following operations:

- **NOP** – No operation  
- **LDA** – Load accumulator from memory  
- **ADD**, **SUB** – Arithmetic operations  
- **LDI** – Load immediate value  
- **JMP**, **JNZ** – Control flow operations  
- **SWAP** – Exchange values  
- **MOVAB**, **MOVBA** – Register moves  
- **LSHIFT**, **RSHIFT** – Bitwise shifts  
- **OUT** – Output result  
- **HLT** – Halt program  

Each instruction is executed using microinstructions governed by a control word from EEPROM.

---

## 🧪 Sample Programs

Sample programs are provided in the form of `report.pdf`.


### 🔗 Connect

GitHub: Rishikaa007

Email: vermarishika709@gmail.com
