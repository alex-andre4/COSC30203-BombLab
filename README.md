# 💣 Bomb Lab – COSC 30203

This repository contains my work on the **Bomb Lab** project for *COSC 30203: Computer System Fundamentals* at TCU (Fall 2024). The goal of this lab was to reverse engineer and defuse a binary bomb using GDB and x86 assembly analysis.

## 🧠 Objective

Each student was given a unique binary containing multiple "phases" that had to be defused by providing exact input strings. Supplying incorrect input would cause the bomb to "explode" (terminate execution). The goal was to analyze the binary, understand its logic, and determine the correct inputs for all phases.

## 🔧 Tools & Skills Used

- `GDB` (GNU Debugger) for disassembly, breakpoints, and memory inspection  
- `objdump` for analyzing symbols and disassembled code  
- `strings` utility to search embedded readable strings  
- Reverse engineering x86 assembly  
- Understanding of stack frames, registers, and control flow  
- Careful debugging and problem-solving under constraints

## 📂 Files Included

- `psol.txt` – Final solution file with the correct inputs for each bomb phase  
- `bomblab.pdf` – Project instructions and description 

## 🛑 Academic Integrity Notice

This repository is for **educational and portfolio purposes only**. Please do not copy or use any part of this work in active or future coursework. Doing so may violate academic integrity policies.

## 📜 License

This project is licensed under the [MIT License](LICENSE).
