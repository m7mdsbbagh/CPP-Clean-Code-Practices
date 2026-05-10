# 🎲 Random Array Even Number Counter

![C++](https://img.shields.io/badge/Language-C%2B%2B-blue?style=flat-square&logo=c%2B%2B)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat-square)
![Level](https://img.shields.io/badge/Level-Beginner-orange?style=flat-square)
![Year](https://img.shields.io/badge/Year-1st%20Year-purple?style=flat-square)

> A simple C++ console program that generates a random array and counts how many even numbers are in it — built as part of my first-year programming journey.

---

## 📌 About The Project

This project was one of my early exercises in understanding **arrays**, **functions**, and **random number generation** in C++.

The program:
- Asks the user to enter how many elements they want (between 1 and 100)
- Fills an array with random numbers from 1 to 100
- Displays the array
- Counts and shows how many numbers are even

It also uses a **function pointer** (`bool (*condition)(int)`) to make the counter reusable for any condition — a concept I was just starting to learn!

---

## 🚀 How It Works

```
Enter number of elements (1 - 100): 10

Array Elements:
23 88 45 12 67 34 90 11 56 77

The count of even numbers is: 4
```

---

## 🛠️ Features

| Feature | Description |
|--------|-------------|
| 🔢 Input Validation | Keeps asking until the user enters a valid range |
| 🎲 Random Generation | Fills array with random numbers using `rand()` and `srand()` |
| 🔍 Condition Counter | Uses a function pointer to count elements by any condition |
| 📋 Array Printer | Displays all array elements in one line |

---

## 📂 File Structure

```
📁 project/
└── 📄 main.cpp       ← The entire program (single file)
```

---

## ⚙️ How To Run

**Requirements:** Any C++ compiler (g++, MSVC, etc.)

```bash
# Compile
g++ main.cpp -o program

# Run
./program
```

---

## 🧠 What I Learned

- Declaring and using **arrays** in C++
- Writing and calling **custom functions**
- Using **`rand()` and `srand()`** for random numbers
- Validating user input with a **`do-while` loop**
- My first experience with **function pointers**

---

## 🌱 What I'd Improve Later

- [ ] Use `std::vector` instead of a fixed-size array
- [ ] Add support for counting odd numbers too
- [ ] Use `std::mt19937` for better randomness
- [ ] Add input error handling for non-integer input

---

## 👨‍💻 Author

**Mohammad Al-Sabbagh**
🎓 First-Year CS Student — Al-Balqa Applied University, Ajloun College

---

*This is one of my early programming projects. I'm still learning, and every line of code is a step forward! 💪*
