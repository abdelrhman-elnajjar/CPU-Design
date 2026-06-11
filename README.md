# Simple CPU Design — Logisim Evolution

A fully functional 16-bit CPU designed and simulated using **Logisim Evolution**. The project implements a complete computer architecture including a Control Unit, Data Unit, ALU, Memory, and I/O system.

---

## 📐 Architecture Overview

The CPU is composed of the following main components:

| Component | Description |
|---|---|
| **Control Unit** | Generates control signals to coordinate all CPU operations |
| **Data Unit** | Contains registers (AC, DR, AR, IR, PC, OUTR, INPR) and manages data flow |
| **ALU** | Supports ADD, AND, CMA (complement accumulator) operations |
| **RAM** | Main memory for instruction and data storage |
| **Input/Output** | DipSwitch for input, LED display for output |

---

## 🔧 Registers

| Register | Full Name | Purpose |
|---|---|---|
| **AC** | Accumulator | Stores ALU results |
| **DR** | Data Register | Holds data read from memory |
| **AR** | Address Register | Holds memory address |
| **IR** | Instruction Register | Holds current instruction |
| **PC** | Program Counter | Tracks next instruction address |
| **OUTR** | Output Register | Sends data to output device |
| **INPR** | Input Register | Receives data from input device |

---

## ⚙️ ALU Operations

- **ADD** — Adds DR to AC
- **AND** — Bitwise AND between DR and AC
- **CMA** — Complements the Accumulator

---

## 🛠️ Tools Used

- [Logisim Evolution v4.0.0](https://github.com/logisim-evolution/logisim-evolution)

---

## 🚀 How to Run

1. Download and install [Logisim Evolution](https://github.com/logisim-evolution/logisim-evolution/releases)
2. Clone this repository:
   ```bash
   git clone https://github.com/abdelrhman-elnajjar/progect_Abdelrhman
   ```
3. Open `PROJECT_HIMA.circ` in Logisim Evolution
4. Press **Simulate → Enable Clock** to start the simulation

---

## 📁 Project Structure

```
├── PROJECT_HIMA.circ   # Main Logisim circuit file
└── README.md
```

---

## 👤 Author

**Abdelrhman Elnagar**  
[GitHub](https://github.com/abdelrhman-elnajjar)
