# Data Structures and Algorithms Lab

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python) ![Course](https://img.shields.io/badge/Course-23CSE203-orange) ![Status](https://img.shields.io/badge/Status-Lab%20Work-success)

A collection of **Data Structures and Algorithms laboratory programs implemented in Python** as part of the **23CSE203 – Data Structures and Algorithms** course.

This repository contains programs practiced and documented across **7 lab weeks**, including recursion, searching, sorting, linked lists, stacks, queues, and circular queues. The laboratory work also includes explanations, sample outputs, debugging, and errors encountered during implementation.

---

## 👨‍🎓 Student Details

| **Details**         | **Information**                |
| ------------------- | ------------------------------ |
| **Name**            | JASHTI HEMENDRA                |
| **Roll No.**        | AV.SC.U4CSE25116               |
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

The first week focuses on understanding recursion and recursive function calls.

Programs include:

#### 1A. Recursive Countdown

A recursive Python program to display a countdown from `n` to `1`, followed by `"launch"`.

#### 1B. Recursive Compound Growth Factor

A recursive program for calculating the compound growth factor.

#### 1C. Recursive Employee ID Search

A recursive program to search for an employee ID in a list.

#### 1D. Recursive Factorial Calculation

A recursive program to calculate factorial values.

#### 1E. Recursive Fibonacci Series

A recursive program to generate the Fibonacci series.

The recursion exercises also document common errors such as incorrect recursive calls and `RecursionError`.

---

## Week 2 — Searching

The second week focuses on searching techniques.

### 2A. Linear Search

The program searches for a given element by checking the elements of the array one by one.

Features:

* Takes array size and elements from the user
* Accepts a search key
* Searches each element sequentially
* Returns the position/index when the element is found
* Indicates when the element is not found

### 2B. Binary Search — Sorted Array

The program performs binary search on a sorted array.

The algorithm uses:

* Left boundary
* Right boundary
* Middle position

The search space is repeatedly reduced until the element is found or the search ends.

### 2C. Binary Search — Unsorted Array

The program accepts an unsorted array and sorts it before applying binary search.

Steps include:

1. Take the input array
2. Check the array
3. Sort the array when required
4. Perform binary search
5. Display the result

---

# Week 3 — Sorting

The third week focuses on fundamental sorting algorithms.

## 3A. Bubble Sort

Bubble Sort repeatedly compares adjacent elements and swaps them when they are in the wrong order.

Example:

```text
Input:
1 15 23 12 5

Output:
[1, 5, 12, 15, 23]
```

The process is repeated until the elements are arranged in ascending order.

---

## 3B. Insertion Sort

Insertion Sort considers the first element as sorted and inserts each subsequent element into its correct position.

Example:

```text
Input:
1 5 2 9 3

Output:
[1, 2, 3, 5, 9]
```

---

## 3C. Selection Sort

Selection Sort finds the smallest element from the unsorted portion and places it at the current position.

Example:

```text
Input:
1 10 8

Output:
[1, 8, 10]
```

---

## 3D. Merge Sort

Merge Sort uses a divide-and-conquer approach.

The array is:

1. Divided into smaller parts
2. Recursively sorted
3. Merged into a sorted array

---

## 3E. Quick Sort

Quick Sort uses a pivot and partitioning technique.

The program:

1. Selects a pivot
2. Partitions the array
3. Sorts the left part
4. Sorts the right part recursively

---

# Week 4 — Linked Lists

The fourth week focuses on linked-list data structures and their operations.

## 4A. Singly Linked List

The program implements a singly linked list with menu-driven operations.

Operations include:

* Create a linked list
* Insert at beginning
* Insert at end
* Insert at specific index
* Delete by value
* Delete at beginning
* Delete at the end
* Count number of nodes
* Display / Traverse
* Exit

---

## 4B. Doubly Linked List

The program implements a doubly linked list where each node maintains references to both the previous and next nodes.

Operations include:

* Create a linked list
* Insert at beginning
* Insert at end
* Insert at specific index
* Delete by value
* Delete at beginning
* Delete at end
* Count number of nodes
* Display / Traverse
* Exit

---

## 4C. Circular Linked List

The program implements a circular singly linked list.

In a circular linked list, the last node points back to the first node.

The important connection maintained is:

```python
tail.next = head
```

Operations include:

* Create a linked list
* Insert at beginning
* Insert at end
* Insert at specific index
* Delete by value
* Delete at beginning
* Delete at end
* Count number of nodes
* Display / Traverse
* Exit

---

# Week 5 — Stack

The fifth week focuses on implementing stacks.

## 5A. Stack Using Array

The stack is implemented using a Python list.

Operations include:

* Push
* Pop
* Peek
* Display

The stack follows the **LIFO (Last In, First Out)** principle.

### Basic operations

```python
stack.append(10)
```

Pushes an element into the stack.

```python
stack.pop()
```

Removes the top element.

```python
stack[-1]
```

Accesses the top element.

---

## 5B. Stack Using Linked List

The stack is implemented using nodes and a `top` pointer.

Operations include:

* Push
* Pop
* Peek
* Display
* Count

The `top` pointer represents the top element of the stack.

---

# Week 6 — Stack Using Array and Linked List

This week implements stack operations using both an array and a linked list.

### Operations

* Push
* Pop
* Peek
* Display

### Stack using Array

The array/list implementation uses a list to store elements and performs stack operations using list functions.

### Stack using Linked List

The linked-list implementation uses:

* `Node`
* `top`
* `next`

The push operation adds a new node at the top, while pop removes the top node.

The programs also handle conditions such as:

* Stack Overflow
* Stack Underflow
* Empty Stack

---

# Week 7 — Queue

The seventh week focuses on queue implementations.

## 7A. Queue Using Array and Linked List

The program implements a Queue using both:

* Array
* Linked List

A main menu is provided to select the implementation.

### Operations

* Enqueue
* Dequeue
* Peek
* Display

The queue follows the **FIFO (First In, First Out)** principle.

### Array Queue

The queue uses a Python list to store elements.

Example:

```python
queue.append(10)
```

Enqueues an element.

```python
queue.pop(0)
```

Dequeues an element.

### Linked List Queue

The linked-list implementation uses:

* `front`
* `rear`
* `Node`

The element is inserted at the rear and removed from the front.

---

## 7B. Circular Queue Using Array and Linked List

The program implements a Circular Queue using:

* Array
* Linked List

A main menu is provided to select the implementation.

### Operations

* Enqueue
* Dequeue
* Peek
* Display

### Circular Queue Using Array

The array implementation uses `front` and `rear` positions.

Circular movement is performed using:

```python
rear = (rear + 1) % size
```

and:

```python
front = (front + 1) % size
```

The full condition is:

```python
(rear + 1) % size == front
```

The empty condition is:

```python
front == -1
```

### Circular Queue Using Linked List

The linked-list implementation maintains a circular connection:

```python
rear.next = front
```

This allows the last node to point back to the first node.

---

# 🧠 Concepts Covered

* Python Programming
* Functions
* Recursion
* Arrays
* Python Lists
* Linear Search
* Binary Search
* Bubble Sort
* Insertion Sort
* Selection Sort
* Merge Sort
* Quick Sort
* Singly Linked List
* Doubly Linked List
* Circular Linked List
* Stack
* Queue
* Circular Queue
* Classes and Objects
* Nodes and Pointers/References
* Menu-driven Programs
* User Input Handling
* Algorithm Implementation
* Debugging
* Error Handling

---

# 🔄 Data Structure Principles

## Stack

**LIFO — Last In, First Out**

```text
Push → Add element
Pop  → Remove top element
Peek → View top element
```

## Queue

**FIFO — First In, First Out**

```text
Enqueue → Add at rear
Dequeue → Remove from front
Peek    → View front element
```

## Circular Queue

A circular queue allows the queue to reuse available positions by connecting the end back to the beginning.

---

# 🐛 Errors & Debugging

The laboratory work also documents errors encountered during program implementation and their corrections.

Common errors include:

| **Error**         | **Cause / Problem**                                          |
| ----------------- | ------------------------------------------------------------ |
| `SyntaxError`     | Incorrect Python syntax                                      |
| `TypeError`       | Incorrect data type or operation                             |
| `ValueError`      | Invalid input value                                          |
| `IndexError`      | Invalid list/array index                                     |
| `AttributeError`  | Incorrect attribute or method                                |
| `NameError`       | Variable or object was not defined                           |
| `RecursionError`  | Incorrect or infinite recursion                              |
| Stack Underflow   | Pop performed on an empty stack                              |
| Stack Overflow    | Inserting beyond the stack limit                             |
| Queue Empty       | Dequeue/Peek performed before insertion                      |
| Queue Full        | Circular queue has no available space                        |
| Infinite Loop     | Incorrect linked-list traversal condition                    |
| Incorrect Sorting | Wrong comparison or swapping condition                       |
| Pointer Error     | Incorrect `front`, `rear`, `head`, `tail`, or `top` handling |

These errors were identified and corrected during the implementation and testing of the programs.

---

# 🛠️ Technologies Used

* **Python 3**
* Python Lists
* Functions
* Loops
* Conditional Statements
* Recursion
* Classes and Objects
* Linked Lists
* Stack
* Queue
* Circular Queue

---

# ▶️ How to Run

## 1. Clone the Repository

```bash
git clone <your-repository-url>
```

## 2. Navigate to the Repository

```bash
cd lab_dsa
```

## 3. Run a Python Program

```bash
python filename.py
```

Replace `filename.py` with the required program file.

---

# 📁 Repository Structure

```text
lab_dsa/
│
├── README.md
│
├── Week-1/
│   ├── 1A
│   ├── 1B
│   ├── 1C
│   ├── 1D
│   └── 1E
│
├── Week-2/
│   ├── 2A
│   ├── 2B
│   └── 2C
│
├── Week-3/
│   ├── 3A
│   ├── 3B
│   ├── 3C
│   ├── 3D
│   └── 3E
│
├── Week-4/
│   ├── 4A
│   ├── 4B
│   └── 4C
│
├── Week-5/
│   ├── 5A
│   └── 5B
│
├── Week-6/
│   ├── 6A
│   └── 6B
│
└── Week-7/
    ├── 7A
    └── 7B
```

---

# 🎯 Learning Objectives

By completing these laboratory programs, the following concepts are practiced:

1. Understanding recursive problem solving
2. Implementing searching algorithms
3. Implementing sorting algorithms
4. Understanding linked-list structures
5. Implementing singly linked lists
6. Implementing doubly linked lists
7. Implementing circular linked lists
8. Implementing stacks using arrays
9. Implementing stacks using linked lists
10. Implementing queues using arrays
11. Implementing queues using linked lists
12. Implementing circular queues
13. Understanding LIFO and FIFO principles
14. Handling user input
15. Debugging Python programs
16. Understanding program execution and output

---

# 📖 Course Information

**Course:** Data Structures and Algorithms
**Course Code:** 23CSE203
**Credits:** 5
**Department:** School of Computing
**Institution:** Amrita Vishwa Vidyapeetham

---

# 👤 Author

**JASHTI HEMENDRA**

**Roll No:** AV.SC.U4CSE25116

**CSE-B | 2nd Year | 3rd Semester**

---

> This repository contains academic laboratory work completed as part of the Data Structures and Algorithms course.
