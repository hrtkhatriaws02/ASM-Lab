# 🖥️ IBM-ASM-Programs (Mainframe Assembly)

This repository contains personal practice programs written in **IBM Mainframe Assembly Language (HLASM)**. Each program demonstrates specific low-level system concepts, operations, or features of the z/Architecture.

---

## 📁 Repo Structure

- `*.asm` — HLASM source modules
- `index.txt` — List of modules with short descriptions
- `README.md` — This file

---

## 🗂️ index.txt Format

Each line provides a brief summary of what the module does.

### Example:
hrtk0001.asm - Print "Shree Ganeshay Namah!" to the console

---

## ⚙️ Assembling & Running (on z/OS)

Programs can be assembled using **HLASM** and executed via **JCL** or submitted in TSO/ISPF. Typical execution steps:

1. Allocate PDS for source code and object code
2. Use **IEFBR14** or custom JCL to submit
3. Assemble using JCL job or ISPF panel
4. Run using `GO` step or a testing harness

---

## 🎯 Goals

- Practice **z/Architecture assembly**
- Understand mainframe registers, PSW, data definitions, storage formats
- Learn basics of **WTO, SVC**, macros, loops, and condition codes

---

## 📌 Naming Convention

Files are named in the format:
hrtkXXXX.asm

Where `XXXX` is a sequential number.

---

## 🧠 Notes

- Comments inside each `.asm` file help explain logic
- Focus is on **clarity**, not complexity
- Suitable for **students**, **mainframe developers**, or anyone preparing for **Assembler interviews or certifications**

---

## 📄 License

This project is open-source and licensed under the [MIT License](LICENSE).

---

Happy Coding in Hex! 🧬
