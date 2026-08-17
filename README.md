# Data Structures and Algorithms Lab

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Course](https://img.shields.io/badge/Course-23CSE203-orange)
![Status](https://img.shields.io/badge/Status-Lab%20Work-success)

A collection of **Data Structures and Algorithms laboratory programs implemented in Python** as part of the **23CSE203 – Data Structures and Algorithms** course.

The repository contains programs practiced and documented through different lab weeks, along with sample outputs, explanations, and errors encountered during implementation.

---

## 👨‍🎓 Student Details

| Details             | Information                    |
| ------------------- | ------------------------------ |
| **Name**            | JASHTI HEMENDRA                |
| **Roll No**         | AV.SC.U4CSE25116               |
| **Year / Semester** | 2nd Year / 3rd Semester        |
| **Section**         | CSE-B                          |
| **Course**          | Data Structures and Algorithms |
| **Course Code**     | 23CSE203                       |
| **Credits**         | 5                              |
| **Department**      | School of Computing            |
| **Faculty**         | Dr. Raj Kumar Batchu           |

---

## 📚 Lab Contents

### Week 1 — Recursion

The first part of the lab focuses on understanding recursion and recursive function calls.

Programs include:

* Recursive number printing using `launch()`
* Power calculation using recursion
* Employee ID searching
* Fibonacci series using recursion
* Factorial calculation using recursion

## The recursion exercises also document common errors such as `TypeError` and `RecursionError`, along with their observed outputs.

### Week 2 — Searching

The second week focuses on searching techniques.

#### 1. Linear Search

The program searches for a given element by checking the elements of the array one by one.

* Takes array size and elements from the user
* Accepts a search key
* Returns the index when the key is found
* Returns `-1` when the key is not found

#### 2. Binary Search — Unsorted Array

The program accepts an unsorted array and sorts it before applying binary search.

* Checks whether the array is sorted
* Sorts the array when required
* Performs binary search
* Displays whether the element was found

#### 3. Binary Search — Sorted Array

Binary search is directly performed on the supplied array.

The algorithm uses left and right limits and repeatedly calculates the middle index to reduce the search space.

---

### Week 3 — Sorting

The third week focuses on fundamental sorting algorithms.

#### 1. Bubble Sort

Bubble Sort repeatedly compares adjacent elements and swaps them when they are in the wrong order.

Example:

```text
Input:
1 15 23 12 5

Output:
[1, 5, 12, 15, 23]
```

#### 2. Insertion Sort

Insertion Sort considers the first element as sorted and inserts each subsequent element into its correct position.

Example:

```text
Input:
1 5 2 9 3

Output:
[1, 2, 3, 5, 9]
```

#### 3. Selection Sort

Selection Sort finds the smallest element from the unsorted portion and swaps it with the element at the current position.

Example:

```text
Input:
1 10 8

Output:
[1, 8, 10]
```

---

## 🧠 Concepts Covered

* Recursion
* Functions
* Arrays / Lists
* Linear Search
* Binary Search
* Bubble Sort
* Insertion Sort
* Selection Sort
* User input handling
* Iteration and loops
* Swapping elements
* Error identification and debugging

---

## 🛠️ Technologies Used

* **Python 3**
* Python Lists
* Functions
* Loops
* Conditional Statements
* Recursion

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone <your-repository-url>
```

### 2. Navigate into the project

```bash
cd lab_dsa
```

### 3. Run a Python program

```bash
python filename.py
```

> Replace `filename.py` with the required program file.

---

## 📁 Suggested Repository Structure

```text
lab_dsa/
│
├── README.md
│
├── lab1/
│   ├── lab1_1.py
│   ├── lab1_2.py
│   ├── lab1_3.py
│   |__ lab1_4.py
|   └── lab1_5.py
│   
├── lab2/
│   ├── lab2_1.py
│   ├── lab2_2.py
│   └── lab2_3.py
│
└── lab3/
    ├── 3.1.py
    ├── 3.2.py
    └── 3.3.py
```

*The structure above is a suggested organization for keeping the lab programs separated by week.*

---

## 🐛 Errors & Debugging

The lab manual also records errors encountered while writing and executing the programs.

Some examples include:

* `TypeError`
* `IndexError`
* `RecursionError`
* `SyntaxError`
* Incorrect sorting due to comparison operators
* Incorrect use of logical operators

For example, during Bubble Sort, a missing colon in the `if` statement resulted in a syntax error. During Selection Sort, using `>` instead of `<` produced reverse sorting instead of the expected ascending order.
These errors are included as part of the learning and debugging process.

---

## 🎯 Learning Objectives

By completing these programs, the lab work focuses on developing an understanding of:

1. Recursive problem solving
2. Searching techniques
3. Sorting techniques
4. Array/list manipulation
5. Algorithmic thinking
6. Debugging Python programs
7. Understanding program execution and output

---

## 📖 Reference

**Course:** Data Structures and Algorithms
**Course Code:** 23CSE203
**Institution:** Amrita Vishwa Vidyapeetham
**Department:** School of Computing

---

## 👤 Author

**JASHTI HEMENDRA**

**Roll No:** AV.SC.U4CSE25116

**CSE-B | 2nd Year | 3rd Semester**

---

> This repository contains academic laboratory work completed as part of the Data Structures and Algorithms course.
