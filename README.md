
# CSA-CPU-Sim-Lab
## Computer System Architecture – CPU Sim Lab

**Name:** Aditya Agarwal  
**Roll No.:** 26570003  
**Course / Semester:** B.Sc. (Hons.) Computer Science, Semester 1  
**College:** Ramanujan College, University of Delhi  
**Paper:** Computer System Architecture  

---

## About the Project

This repository contains practical work based on Mano's Basic Computer, implemented and simulated using CPU Sim 4.0.11.

Each practical is organised into a separate folder containing relevant machine files, assembly programs (where applicable), and screenshots demonstrating execution and output.

## Repository Structure

```text
CSA-CPU-Sim-Lab/
│
├── README.md
├── BASIC_COMPUTER.CPU
│
├── PRACTICAL_01_CREATE_MACHINE/
├── PRACTICAL_02_FETCH_ROUTINE/
├── PRACTICAL_03_ADD/
├── PRACTICAL_04_SUBTRACT/
├── PRACTICAL_05_LOGICAL_OPS/
├── PRACTICAL_06_MEMORY_REFERENCE/
├── PRACTICAL_07_CLA_CMA_CME_HLT/
├── PRACTICAL_08_INC_SPA_SNA_SZE/
├── PRACTICAL_09_CIR_CIL/
├── PRACTICAL_10_SUM_UNTIL_NEGATIVE/
└── PRACTICAL_11_SUM_UNTIL_ZERO/
```

Each practical folder contains screenshots documenting the corresponding practical work.

## Software Requirements

- Java 8 with JavaFX
- CPU Sim 4.0.11

## How to Run

1. Install Java 8 with JavaFX (for example, Azul Zulu JDK FX 8).
2. Download and launch CPU Sim 4.0.11.
3. Open CPU Sim and navigate to **File → Open Machine**.
4. Select `BASIC_COMPUTER.CPU`.
5. If an assembly (`.a`) program is available, open it using **File → Open Text**.
6. Press **Ctrl + 2** to assemble and load the program.
7. Press **Ctrl + R** to execute the program.
8. To execute instructions step by step, use **Ctrl + D** to enter debug mode and select *Step by Instr* or *Step by Micro*.
9. For programs requiring input, enter the required value in the yellow console and press Enter.

## Notes

1. Practical 02 uses the same machine file created in Practical 01. Its screenshots demonstrate the fetch routine being executed one microinstruction at a time.
2. Register values in debug traces are displayed in **Unsigned Decimal** format.
3. The RAM pane displays values in **Hexadecimal** format.
4. Screenshots are provided as documentation of practical execution and output.

---

## Author

**Aditya Agarwal**  
B.Sc. (Hons.) Computer Science  
Ramanujan College, University of Delhi
