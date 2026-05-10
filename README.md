<div align="center">
  <h1> C++ Array Logic & Operations </h1>
  <p><i> Clean Code. Generic Programming. Memory Safety. </i></p>
</div>

---

> A personal implementation focusing on building robust algorithms. This project steps away from rigid coding structures to embrace dynamic, reusable, and secure C++ logic.

## ✦ The Concept
This program isn't just about counting numbers; it's about software architecture. By utilizing **Function Pointers**, the counting logic is completely separated from the condition logic. You can count even, odd, or prime numbers without changing the core engine.

## ✦ Core Architecture

| Principle | How it is Applied |
| :--- | :--- |
| **Generic Design** | Uses `bool (*condition)(int)` to pass different rules dynamically. |
| **Input Security** | Employs a strict `readNumInRange` loop to prevent memory overflow. |
| **Data Efficiency** | Strategically uses `short` datatypes to optimize system memory. |

## ✦ Quick Start

**1. Compile the code:**
```cmd
g++ -o app mainGenericConditionCounter.cpp
```
**2. Run the program:**
```cmd
app.exe
```
## ✦ Terminal Output
```cmd
Enter number of elements (1 - 100): 10

Array Elements:
34 7 88 12 95 3 22 56 71 18 

The count of even numbers is: 6
