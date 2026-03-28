# ⚛️ Quantum Circuit Implementations – Hackathon Project

## 🚀 Overview

This repository contains multiple quantum computing problems implemented as part of a hackathon. The focus is on applying quantum logic and digital design concepts to solve computational and real-world problems.

---

## 🧠 Implemented Problems

### 🔹 Level 1: Ripple Carry Adder (RCA)

* Designed a 4-bit quantum ripple carry adder
* Performs binary addition using quantum gates
* Verified results using simulation

#### ⚙️ Gates Used

* X (NOT)
* CX (CNOT)
* CCX (Toffoli)

#### 📥 Example

```text
A = 0101 (5)
B = 0011 (3)
```

#### 📤 Output

```text
Sum = 1000 (8)
Carry = 0
```

---

### 🔹 Level 3: Smart City Emergency Signal Selector (MUX)

A combinational logic system designed for efficient emergency handling in a smart city.

#### 🚨 Problem

Multiple sensors generate signals:

* Fire detection
* Gas leakage
* Intrusion detection
* Medical emergency

Due to limited bandwidth, only one signal can be transmitted at a time.

---

#### ⚙️ Solution

* Implemented a **Multiplexer (MUX)**
* Applied **priority logic** to select the most critical signal
* Ensured single output transmission

---

#### 🧠 Priority Example

```text
Fire > Medical > Gas > Intrusion
```

---

## ⚙️ Technologies Used

* Python
* Qiskit
* Quantum Circuit Simulation
* Digital Logic Design

---

## ▶️ How to Run

```bash
pip install qiskit
python main.py
```

---

## 📊 Key Features

* Quantum circuit design and simulation
* Arithmetic operations using quantum logic
* Real-world system design using MUX
* Circuit visualization

---

## 🧠 Learning Outcomes

* Understanding of quantum gates and circuits
* Implementation of ripple carry adder
* Application of combinational logic (MUX)
* Practical problem-solving

---

## 🏁 Conclusion

This project demonstrates how **quantum computing and classical logic design** can be combined to solve both computational and real-world problems.

---

⭐ Hackathon Project | Quantum Computing + Digital Logic
