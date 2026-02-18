# 🧩 Sudoku Solver (C++)

A console-based **Sudoku Solver** developed in **C++** using the **Backtracking algorithm**.  
This project demonstrates problem-solving, recursion, and constraint validation in a clean and efficient way.

The solver takes a partially filled **9×9 Sudoku grid** and automatically completes it while following standard Sudoku rules.

---

## 🎥 Project Demo Video

📺 **Watch the full project explanation and demo here:**  
👉 https://drive.google.com/file/d/1WQR7B4ZJAPVXx0ukzr2qrb5cOGHwGAU8/view?usp=sharing

The video explains:
- Project overview
- Algorithm logic (Backtracking)
- Code walkthrough
- Live program execution

---

## 📌 Project Overview

The purpose of this project is to apply **core C++ programming concepts** and **algorithmic thinking** to solve a real-world logic problem.

Instead of relying on user input (which can cause input errors during demos), this version uses a **built-in Sudoku puzzle** to ensure smooth execution and accurate results.

---

## ✨ Features

✅ Solves any valid 9×9 Sudoku puzzle  
🔁 Uses **Backtracking Algorithm**  
🧠 Validates row, column, and 3×3 sub-grid constraints  
🖥 Console-based (simple & lightweight)  
📊 Displays both the original and solved Sudoku grid  

---

## 🧠 Algorithm Used

### Backtracking Algorithm

The solver:
- Finds an empty cell (represented by `0`)
- Tries numbers from **1 to 9**
- Checks if the number is valid:
  - Not repeated in the row
  - Not repeated in the column
  - Not repeated in the 3×3 sub-grid
- Recursively continues
- Backtracks if a number leads to an invalid solution

This guarantees a correct solution if one exists.

---

## 🛠 Technologies Used

- **Language:** C++
- **Compiler:** GCC (MinGW)
- **IDE:** Visual Studio Code
- **Platform:** Windows (Console Application)
- **Version Control:** Git & GitHub

---

## ▶️ How to Compile & Run

### 1️⃣ Open Terminal in Project Folder
```bash
cd path/to/project-folder
```
### 2️⃣ Compile the Program
```bash
g++ sudokusolver.cpp -o sudoku
```
### 3️⃣ Run the Program
```bash
./sudoku
```
# 📌 Internship Note

This project was developed as part of my internship tasks and focuses on strengthening algorithmic thinking, recursion, and clean C++ implementation.
