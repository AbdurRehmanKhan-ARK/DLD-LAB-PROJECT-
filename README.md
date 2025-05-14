# 6-Bit Arithmetic Logic Unit (ALU)

## 👥 Group Members
- **Syed Muhammad Sufyan**  
- **Faizan Basheer** 
- **Abdur Rehman Khan** 

---

## 📌 Abstract

This project presents the design and implementation of a 6-bit Arithmetic Logic Unit (ALU) capable of performing 16 distinct arithmetic, logical, shift, and comparison operations. Designed using Logisim in a hierarchical approach, the ALU simulates the core computational component of a CPU, offering hands-on experience in digital logic design and computer architecture.

---

## 🎯 Objectives

### ✔ Functional Goals:
- Perform arithmetic operations: Addition, Subtraction, Multiplication, Division  
- Implement logic operations: AND, OR, NOT, XOR  
- Execute shift operations: Left Shift, Right Shift  
- Support comparison and utility operations: Increment, Decrement, Equality, Less Than, Greater Than, Parity Check  

### ✔ Educational Purpose:
- Understand how basic gates form complex circuits  
- Experience in hierarchical, modular circuit design  
- Explore CPU-like operation selection and control using opcodes  

---

## 🔍 Background

An ALU (Arithmetic Logic Unit) is a fundamental block in any CPU responsible for computation. This project recreates ALU behavior at a simplified 6-bit scale using only Logisim’s built-in tools to simulate:

- Binary number representation  
- Combinational logic design  
- Operation multiplexing and control  

---

## 🛠 Tools Used

- **Software:** [Logisim-win v2.7.1](http://www.cburch.com/logisim/)  
- **Components:** All built-in Logisim components (No external libraries or plugins used)  

---

## 🧩 Design Methodology

### 🔝 Top-Down Design Approach
Starting from basic gates (AND, OR, NOT), we designed:
- Half Adders and Full Adders
- Arithmetic, Logic, and Shift units
- Integrated all subcircuits into a single Main ALU circuit

### ⚙️ Core Modules

#### 🔢 Arithmetic Unit
- **6-Bit Adder** – Uses Full Adders  
- **6-Bit Subtractor** – Uses 2’s complement logic  
- **6-Bit Multiplier** – Iterative addition approach  
- **6-Bit Divider** – Repeated subtraction logic  

#### 🧪 Logic Unit
- Bitwise **AND**, **OR**, **XOR**, **NOT** operations on 6-bit inputs  

#### 🔁 Shift Unit
- **Left Shift**: Logical shift with zero padding  
- **Right Shift**: Logical shift with zero padding  

#### ⚖ Comparison Unit
- **Equal (A == B)**  
- **Less Than (A < B)**  
- **Greater Than (A > B)**  

#### 🔼 Increment/Decrement
- **Increment**: A + 1  
- **Decrement**: A - 1  

#### 🚩 Status Flags
- **Parity Check** – Even or odd number of 1’s in A  
- **Zero Detection** – Outputs true if all bits in A are 0  

---

## 🛰 Control Mechanism

Each operation is selected using **D Flip-Flop controlled switches**.  
- An input signal sets the D input  
- The operation is activated on a clock edge  
- Flip-Flop memory allows only one operation to remain active at a time

This control mechanism better simulates real **CPU instruction latching** and improves stability over toggle switches.

---

## 🧠 Main Circuit Integration

The final ALU circuit integrates:
- All operational modules
- Opcode decoder
- Multiplexers for output selection
- **D Flip-Flop-based instruction control**
- Output indicators for clarity

> **"Behold the Beast: A 6-Bit ALU So Powerful, It Defies Screenshots!"**  
> **"This circuit is so dense, it has its own gravitational pull."**

---

## ✅ Results and Conclusion

### 🏁 Technical Achievements
- Fully functional 6-bit ALU with **16 operations**
- Built using **120+ gates**
- Hierarchical and modular design for maintainability and scalability

### 💡 Key Takeaways
- Deepened understanding of digital logic and computer architecture
- Enhanced skills in simulation, debugging, and teamwork
- Developed a reusable and extensible digital system

### 🚀 Future Scope
- Expand to 8-bit or 16-bit operations  
- Add signed number support  
- Integrate memory units and instruction registers

---

## 💬 Final Words

> "What began as gates ended as growth.  
> Every simulation error, every wire dragged, every logic clash—taught us resilience.  
> This ALU is more than a project; it's proof that logic and learning go hand in hand."

---

## 🔗 License

This project is for educational purposes only and is not licensed for commercial use.


