# DATA STRUCTURES AND ALGORITHMS LAB
## 23CSE203 | Python Implementations

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python) ![Course](https://img.shields.io/badge/Course-23CSE203-orange) ![Status](https://img.shields.io/badge/Status-Lab%20Work-success)

<p align="center">
  <strong>Amrita Vishwa Vidyapeetham</strong><br>
  School of Computing
</p>

<p align="center">
  <strong>2nd Year | Semester 3 | CSE-B</strong>
</p>

---

## 1. About the Repository

Welcome to the **Data Structures and Algorithms Lab (23CSE203)** repository.

This repository contains the practical implementations of various Data Structures and Algorithms concepts using Python, completed as part of the Semester 3 laboratory coursework at Amrita Vishwa Vidyapeetham.

The repository covers fundamental programming concepts, recursive problem-solving, searching and sorting algorithms, linear data structures, non-linear data structures, tree operations, and hashing techniques.

Each experiment focuses on understanding the working principles of an algorithm or data structure through Python programming. The implementations include user input, logical operations, menu-driven programs, output demonstrations, explanations, and error handling wherever documented in the laboratory manual.

The primary objective of this repository is to develop a strong foundation in data structures, understand how algorithms operate internally, and improve logical thinking and problem-solving skills through practical implementation.

## 2. Student Information

| Field | Details |
|---|---|
| Student Name | JASHTI HEMENDRA |
| Roll Number | AV.SC.U4CSE25116 |
| Course Code | 23CSE203 |
| Course Name | Data Structures and Algorithms |
| Academic Year | 2nd Year |
| Semester | Semester 3 |
| Section | CSE-B |
| Credits | 5 |
| Faculty | Dr. Rajkumar Batchu |
| Department | School of Computing |
| Institution | Amrita Vishwa Vidyapeetham |

---

## 3. Technologies and Tools

The following technologies and development tools are used throughout the laboratory exercises.

| Technology / Tool | Purpose |
|---|---|
| Python 3 | Primary programming language |
| Visual Studio Code | Code development and execution |
| Python Interpreter | Running Python programs |
| Git | Version control |
| GitHub | Source code hosting and documentation |

### Programming Concepts Used

- Functions and recursion
- Classes and objects
- Constructors
- Conditional statements
- Loops and iterations
- Lists and arrays
- References and pointers
- Node-based implementations
- Searching and sorting techniques
- Tree traversal algorithms
- Hash functions and collision resolution

---

# 4. Experiments and Implementations

The laboratory manual contains 11 weekly experiments covering different areas of Data Structures and Algorithms.

## WEEK 1 – RECURSION

**Topics:** Recursive Functions and Base Conditions

This experiment focuses on solving problems using recursion. A recursive function calls itself with a smaller or modified input until it reaches a base condition.

### Programs Implemented

**1. Countdown Using Recursion**
- Accept a number from the user.
- Display the countdown from n to 1.
- Print "Launch" after the countdown.
- Use a base condition to terminate recursive calls.

**2. Power Calculation Using Recursion**
- Accept a principal growth factor and number of years.
- Calculate the power using recursive multiplication.
- Use n = 0 as the base condition.
- Return the final value of Pⁿ.

**3. Employee ID Searching**
- Accept employee IDs as a list.
- Search for a given employee ID recursively.
- Compare the current element with the target ID.
- Move to the next index if the element does not match.
- Return True if found and False otherwise.

**4. Factorial Using Recursion**
- Accept a number from the user.
- Calculate its factorial using recursive multiplication.
- Handle negative numbers.
- Use 0! = 1 as the base condition.

**5. Fibonacci Series Using Recursion**
- Generate the first n terms of the Fibonacci series.
- Use two base conditions: n = 0 and n = 1.
- Calculate the next term using the sum of the previous two terms.

**Key Concepts Learned:**
- Recursive function calls
- Base conditions
- Recursive conditions
- Call stack
- Returning values
- Termination of recursive execution

---

## WEEK 2 – SEARCHING ALGORITHMS

**Topics:** Linear Search and Binary Search

This experiment focuses on locating a specific element in a collection of data using different searching techniques.

### Programs Implemented

**1. Linear Search**

Linear Search checks every element sequentially until the required element is found.

Implementation:
- Accept the number of elements.
- Read array elements from the user.
- Accept the target element.
- Traverse the array from the first index.
- Compare every element with the target.
- Return the index if found.
- Return -1 if the element is not present.

**2. Binary Search on a Sorted Array**

Binary Search repeatedly divides the search interval into two halves.

Implementation:
- Initialize `low = 0`.
- Initialize `high = len(arr) - 1`.
- Calculate the middle index.
- Compare the middle element with the target.
- Search the left half if the target is smaller.
- Search the right half if the target is greater.
- Stop when the element is found or the search interval becomes empty.

**3. Binary Search with Unsorted Input**

This program demonstrates how binary search can be performed when the user initially enters an unsorted array.

Implementation:
- Accept an unsorted array.
- Accept the search element.
- Sort the array using `arr.sort()`.
- Display the sorted array.
- Perform binary search on the sorted array.
- Display the position of the element or indicate that it is not found.

**Key Concepts Learned:**
- Sequential searching
- Divide-and-conquer approach
- Array indexing
- Low, high and middle pointers
- Sorted and unsorted data
- Search termination conditions

### Complexity Reference

| Algorithm | Best Case | Average Case | Worst Case |
|---|---:|---:|---:|
| Linear Search | O(1) | O(n) | O(n) |
| Binary Search | O(1) | O(log n) | O(log n) |

---

## WEEK 3 – SORTING ALGORITHMS

**Topics:** Elementary and Advanced Sorting

This experiment introduces different sorting techniques used to arrange elements in ascending order.

### Programs Implemented

**1. Bubble Sort**

Bubble Sort repeatedly compares adjacent elements and swaps them if they are in the wrong order.

Implementation:
- Accept array elements.
- Use an outer loop to control the passes.
- Use an inner loop to compare adjacent elements.
- Swap elements when the left element is greater.
- Repeat until the array is sorted.

**2. Insertion Sort**

Insertion Sort builds a sorted portion of the array by inserting each element into its correct position.

Implementation:
- Consider the first element as sorted.
- Select the next element as the key.
- Compare the key with the previous elements.
- Shift larger elements one position to the right.
- Insert the key into its correct position.

**3. Selection Sort**

Selection Sort repeatedly finds the smallest element from the unsorted portion and places it in the correct position.

Implementation:
- Select the current position.
- Assume the current element is the minimum.
- Compare it with the remaining elements.
- Update the minimum index when a smaller element is found.
- Swap the minimum element with the current element.

**4. Merge Sort**

Merge Sort follows the divide-and-conquer technique.

Implementation:
- Check whether the array contains zero or one element.
- Divide the array into left and right halves.
- Recursively sort both halves.
- Compare elements from both sorted halves.
- Merge them into the original array.
- Copy any remaining elements.

**5. Quick Sort**

Quick Sort uses a pivot element to partition an array.

Implementation:
- Select the last element as the pivot.
- Compare the remaining elements with the pivot.
- Move smaller elements towards the left.
- Place the pivot in its correct position.
- Recursively sort the left and right partitions.

### Complexity Reference

| Algorithm | Best Case | Average Case | Worst Case |
|---|---:|---:|---:|
| Bubble Sort | O(n) | O(n²) | O(n²) |
| Selection Sort | O(n²) | O(n²) | O(n²) |
| Insertion Sort | O(n) | O(n²) | O(n²) |
| Merge Sort | O(n log n) | O(n log n) | O(n log n) |
| Quick Sort | O(n log n) | O(n log n) | O(n²) |

**Key Concepts Learned:**
- Comparison-based sorting
- Swapping and shifting
- Divide and conquer
- Pivot selection
- Partitioning
- Recursive sorting
- Time complexity comparison

---

## WEEK 4 – LINKED LISTS

**Topics:** Singly Linked List, Doubly Linked List and Circular Linked List

This experiment focuses on implementing linked lists using classes and nodes.

### A. Singly Linked List (SLL)

A Singly Linked List consists of nodes where each node contains data and a reference to the next node.

**Node Structure:**

`[Data | Next] → [Data | Next] → None`

**Operations Implemented:**
1. Create a linked list.
2. Insert at the beginning.
3. Insert at the end.
4. Insert at a specific index.
5. Delete by value.
6. Delete at the beginning.
7. Delete at the end.
8. Count the number of nodes.
9. Display or traverse the list.
10. Exit the program.

**Important Concepts:**
- Node creation
- Head and tail references
- Next pointer
- Traversal
- Insertion and deletion
- Updating node references

### B. Doubly Linked List (DLL)

A Doubly Linked List contains references to both the previous and next nodes.

**Node Structure:**

`None ← [Prev | Data | Next] ⇄ [Prev | Data | Next] → None`

**Operations Implemented:**
1. Create a linked list.
2. Insert at the beginning.
3. Insert at the end.
4. Insert at a specific index.
5. Delete by value.
6. Delete at the beginning.
7. Delete at the end.
8. Count the number of nodes.
9. Display or traverse the list.
10. Exit the program.

**Important Concepts:**
- Previous and next references
- Head and tail management
- Forward traversal
- Backward traversal
- Updating both links during insertion and deletion

### C. Circular Linked List (CLL)

A Circular Linked List is a linked list in which the last node points back to the first node.

**Node Structure:**

`HEAD → Node → Node → Node → TAIL`
`  ↑___________________________|`

**Operations Implemented:**
1. Create a circular linked list.
2. Insert at the beginning.
3. Insert at the end.
4. Insert at a specific index.
5. Delete by value.
6. Delete at the beginning.
7. Delete at the end.
8. Count the number of nodes.
9. Display or traverse the list.
10. Display head and tail.
11. Exit the program.

**Important Concepts:**
- Circular connections
- Tail-to-head linking
- Head and tail updates
- Circular traversal
- Avoiding infinite loops

**Key Learning Outcomes:**
- Understanding dynamic data structures
- Creating nodes using Python classes
- Managing references
- Performing insertion and deletion
- Comparing different linked list structures

---

## WEEK 5 – STACK USING ARRAYS AND LINKED LISTS

**Topics:** Stack Data Structure and LIFO Principle

A Stack is a linear data structure that follows the **LIFO (Last In, First Out)** principle.

The last inserted element is the first element removed.

### A. Stack Using Arrays

Implementation uses a Python list to store stack elements.

**Operations:**

| Operation | Description |
|---|---|
| Push | Inserts an element at the top |
| Pop | Removes the top element |
| Peek | Displays the top element without removing it |
| Display | Displays all stack elements |
| Count | Returns the number of elements |

**Important Conditions:**
- Stack Overflow: Occurs when the stack reaches its maximum capacity.
- Stack Underflow: Occurs when pop is performed on an empty stack.

### B. Stack Using Linked Lists

Implementation uses nodes to store stack elements.

**Node Structure:**

`TOP → [Data | Next] → [Data | Next] → None`

**Operations:**
- Push using a new node.
- Pop by updating the top reference.
- Peek using the top node.
- Display through linked list traversal.
- Count by traversing all nodes.

**Key Concepts Learned:**
- LIFO principle
- Top pointer
- Push and pop operations
- Stack overflow and underflow
- Array-based and linked-list-based implementations

---

## WEEK 6 – STACK OPERATIONS USING DIFFERENT IMPLEMENTATIONS

**Topics:** Menu-Driven Stack Implementation

This experiment implements stack operations using both arrays and linked lists through a menu-driven Python program.

### A. Stack Using Array

- Create an empty stack.
- Define the maximum stack size.
- Insert elements using Push.
- Remove elements using Pop.
- Display the top element using Peek.
- Display all stack elements.
- Check overflow and underflow.
- Continue operations until Exit is selected.

### B. Stack Using Linked List

- Create a Node class.
- Initialize the top reference.
- Insert nodes at the top.
- Remove the top node.
- Access the top element.
- Traverse and display all elements.
- Handle empty stack conditions.

**Key Concepts Learned:**
- Stack implementation using different storage structures
- Menu-driven programming
- Class-based implementation
- Pointer/reference handling
- Input validation
- Stack operation management

---

## WEEK 7 – QUEUES AND CIRCULAR QUEUES

**Topics:** FIFO Data Structure

A Queue is a linear data structure that follows the **FIFO (First In, First Out)** principle.

The first inserted element is the first element removed.

### A. Queue Using Array

A Python list is used to store queue elements.

**Operations:**
- Enqueue – Insert an element at the rear.
- Dequeue – Remove an element from the front.
- Peek – Display the front element.
- Display – Show all queue elements.

### B. Queue Using Linked List

A linked list is used to implement the queue.

**Important References:**
- Front – Points to the first node.
- Rear – Points to the last node.

**Operations:**
- Insert a node at the rear.
- Remove a node from the front.
- Display the front element.
- Traverse and display the queue.

### C. Circular Queue Using Array

A Circular Queue connects the last array position back to the first position.

**Important Formulas:**

Circular movement of rear:

`rear = (rear + 1) % size`

Circular movement of front:

`front = (front + 1) % size`

Queue Full Condition:

`(rear + 1) % size == front`

Queue Empty Condition:

`front == -1`

### D. Circular Queue Using Linked List

A linked list is used to implement a circular queue.

**Important Connection:**

`rear.next = front`

**Operations:**
- Enqueue
- Dequeue
- Peek
- Display
- Circular traversal

**Key Concepts Learned:**
- FIFO principle
- Front and rear pointers
- Circular indexing
- Memory reuse
- Queue overflow and underflow
- Circular linked connections

---

## WEEK 8 – BINARY TREES

**Topics:** Binary Tree Implementation Using Arrays and Linked Lists

A Binary Tree is a non-linear data structure in which each node can have at most two children: a left child and a right child.

### A. Binary Tree Using Array

The tree is represented using an array.

**Index Relationships:**

For a node at index `i`:

- Root: Index 0
- Left Child: `2*i + 1`
- Right Child: `2*i + 2`
- Parent: `(i - 1) // 2`

**Operations Documented:**
- Insertion
- Display
- Preorder traversal

### B. Binary Tree Using Linked List

Each node contains:
- Data
- Left child reference
- Right child reference

**Operations Documented:**
- Node creation
- Insertion
- Preorder traversal
- Inorder traversal
- Postorder traversal

**Traversal Techniques:**

| Traversal | Visiting Order |
|---|---|
| Preorder | Root → Left → Right |
| Inorder | Left → Root → Right |
| Postorder | Left → Right → Root |

**Key Concepts Learned:**
- Tree nodes
- Root and child relationships
- Array representation
- Linked representation
- Tree traversal algorithms

---

## WEEK 9 – BINARY SEARCH TREES (BST)

**Topics:** Binary Search Tree Operations and Traversals

A Binary Search Tree is a binary tree in which smaller values are stored in the left subtree and larger values are stored in the right subtree.

### Operations and Concepts

**1. Node Creation**
- Create a node using a class.
- Store the data.
- Maintain left and right references.

**2. Insertion**
- Compare the new value with the root.
- Move left for smaller values.
- Move right for larger values.
- Insert at an empty position.

**3. Searching**
- Compare the search key with the current node.
- Move towards the left or right subtree.
- Stop when the element is found or the node becomes None.

**4. Tree Traversals**

- Inorder: Left → Root → Right.
- Preorder: Root → Left → Right.
- Postorder: Left → Right → Root.

**Important Observation:**

Inorder traversal of a Binary Search Tree displays the elements in ascending order.

**Key Concepts Learned:**
- Binary Search Tree properties
- Recursive insertion
- Searching in trees
- Tree traversal
- Node references
- Handling missing elements

---

## WEEK 10 – AVL TREES

**Topics:** Self-Balancing Binary Search Trees

An AVL Tree is a self-balancing Binary Search Tree. It maintains balance after insertion and deletion operations using rotations.

### Operations Implemented

**1. Node Creation**
- Store the key.
- Maintain left and right references.
- Initialize node height.

**2. Height Calculation**
- Calculate the height of a node.
- Return 0 for an empty node.

**3. Balance Factor**

`Balance Factor = Height(Left Subtree) - Height(Right Subtree)`

**4. Rotations**

Four balancing cases are implemented:

| Case | Rotation |
|---|---|
| LL – Left Left | Right Rotation |
| RR – Right Right | Left Rotation |
| LR – Left Right | Left Rotation followed by Right Rotation |
| RL – Right Left | Right Rotation followed by Left Rotation |

**5. Insertion**
- Insert the key using BST rules.
- Update the height.
- Calculate the balance factor.
- Apply the appropriate rotation when required.

**6. Deletion**
- Search for the required key.
- Handle nodes with zero, one or two children.
- Replace a two-child node using its inorder successor.
- Update heights.
- Rebalance the tree.

**7. Searching**
- Search using BST comparison rules.

**8. Minimum and Maximum**
- Minimum: Move to the leftmost node.
- Maximum: Move to the rightmost node.

**9. Traversal Operations**
- Inorder
- Preorder
- Postorder
- Level-order

**10. Additional Operations**
- Calculate tree height.
- Display the tree structure.
- Handle duplicate values.
- Validate user input.
- Exit using a menu-driven interface.

**Key Concepts Learned:**
- Self-balancing trees
- Height calculation
- Balance factors
- LL, RR, LR and RL rotations
- AVL insertion and deletion
- Tree searching and traversal

---

## WEEK 11 – HASHING

**Topics:** Hash Tables and Collision Resolution Techniques

Hashing is a technique used to map keys to specific positions in a hash table using a hash function.

The experiment demonstrates three different collision resolution techniques.

### Hash Function

The hash table size is initialized as:

`size = 10`

The hash index is calculated using:

`index = key % size`

### A. Separate Chaining

Separate Chaining resolves collisions by maintaining a list at each hash table index.

**Implementation:**
- Create a hash table containing empty lists.
- Calculate the index for each key.
- Insert the key into the corresponding list.
- Store multiple keys at the same index when collisions occur.

### B. Linear Probing

Linear Probing resolves collisions by checking the next available position.

**Formula:**

`new_index = (index + 1) % size`

**Implementation:**
- Create an empty hash table.
- Calculate the hash index.
- Check whether the position is occupied.
- If occupied, move to the next position.
- Insert the key into the first available position.

### C. Quadratic Probing

Quadratic Probing resolves collisions by checking positions using square increments.

**Formula:**

`new_index = (index + i * i) % size`

**Implementation:**
- Calculate the initial hash index.
- Initialize the counter `i = 0`.
- Calculate the next position using quadratic increments.
- Check whether the position is empty.
- Insert the key when an empty position is found.
- Increase the counter when a collision occurs.

### Comparison

| Technique | Collision Resolution |
|---|---|
| Separate Chaining | Stores colliding elements in a list |
| Linear Probing | Checks the next available position |
| Quadratic Probing | Checks positions using square increments |

**Key Concepts Learned:**
- Hash functions
- Hash tables
- Hash index calculation
- Collision detection
- Separate chaining
- Linear probing
- Quadratic probing
- Modulo-based indexing

---

# 5. Experiment Index and Manual Page References

The following references correspond to the printed page numbers in the laboratory manual.

| No. | Experiment | Manual Pages |
|---:|---|---:|
| 01 | Recursion | 4–12 |
| 02 | Searching Algorithms | 13–18 |
| 03 | Sorting Algorithms | 19–32 |
| 04 | Linked Lists | 33–63 |
| 05 | Stack Using Arrays and Linked Lists | 64–72 |
| 06 | Stack Operations | 73–76 |
| 07 | Queues and Circular Queues | 77–93 |
| 08 | Binary Trees | 94–96 |
| 09 | Binary Search Trees | 97–98 |
| 10 | AVL Trees | 99–119 |
| 11 | Hashing | 120–123 |

---

# 6. How to Run the Programs

Follow these steps to execute the programs locally.

### Prerequisites

Install the following:

- Python 3
- Visual Studio Code (recommended)
- Python extension for VS Code

### Step 1 – Clone the Repository

Open the terminal and execute:

```bash
git clone <YOUR-REPOSITORY-URL>
```

### Step 2 – Navigate to the Project Directory

```bash
cd DSA-LAB
```

### Step 3 – Open the Project in VS Code

```bash
code .
```

### Step 4 – Select an Experiment

Navigate to the required weekly experiment folder and open the Python file.

### Step 5 – Execute the Program

```bash
python filename.py
```

On some systems, use:

```bash
python3 filename.py
```

### Step 6 – Provide Input

Enter the values requested by the program in the terminal.

The program will execute the selected algorithm or data structure operations and display the result.

---

# 7. Suggested Repository Structure

The following is a recommended folder organization for maintaining the programs.

```text
DSA-LAB/
│
├── Week-01-Recursion/
│   ├── countdown.py
│   ├── power.py
│   ├── employee_search.py
│   ├── factorial.py
│   └── fibonacci.py
│
├── Week-02-Searching/
│   ├── linear_search.py
│   ├── binary_search.py
│   └── binary_search_unsorted.py
│
├── Week-03-Sorting/
│   ├── bubble_sort.py
│   ├── insertion_sort.py
│   ├── selection_sort.py
│   ├── merge_sort.py
│   └── quick_sort.py
│
├── Week-04-Linked-Lists/
│   ├── singly_linked_list.py
│   ├── doubly_linked_list.py
│   └── circular_linked_list.py
│
├── Week-05-Stack/
│   ├── stack_array.py
│   └── stack_linked_list.py
│
├── Week-06-Stack-Operations/
│   ├── stack_array.py
│   └── stack_linked_list.py
│
├── Week-07-Queues/
│   ├── queue_array_linked_list.py
│   └── circular_queue.py
│
├── Week-08-Binary-Trees/
│   ├── binary_tree_array.py
│   └── binary_tree_linked_list.py
│
├── Week-09-Binary-Search-Tree/
│   └── binary_search_tree.py
│
├── Week-10-AVL-Tree/
│   └── avl_tree.py
│
├── Week-11-Hashing/
│   └── hashing.py
│
└── README.md
```

*Note: This is a suggested structure. The actual filenames and folder names should match the files uploaded to the repository.*

---

# 8. Important Data Structures Covered

| Data Structure | Category | Principle / Property |
|---|---|---|
| Array | Linear | Indexed storage |
| Singly Linked List | Linear | One-way node connection |
| Doubly Linked List | Linear | Two-way node connection |
| Circular Linked List | Linear | Last node connects to first |
| Stack | Linear | LIFO |
| Queue | Linear | FIFO |
| Circular Queue | Linear | Circular indexing |
| Binary Tree | Non-linear | Maximum two children |
| Binary Search Tree | Non-linear | Ordered tree structure |
| AVL Tree | Non-linear | Self-balancing BST |
| Hash Table | Hash-based | Key-to-index mapping |

---

# 9. Important Algorithmic Concepts

The following concepts are demonstrated throughout the experiments.

### Recursion
Solving a problem by repeatedly calling the same function with modified input.

### Searching
Finding the location of a required element in a collection.

### Sorting
Arranging data in a specified order.

### Divide and Conquer
Breaking a problem into smaller subproblems, solving them and combining their results.

### Dynamic Node Linking
Connecting nodes using references instead of storing all elements in consecutive memory locations.

### LIFO
Last In, First Out – the principle followed by stacks.

### FIFO
First In, First Out – the principle followed by queues.

### Tree Traversal
Visiting every node in a tree using a specific order.

### Balancing
Maintaining the height balance of a tree to improve searching and updating operations.

### Hashing
Converting keys into hash table indices and resolving collisions when multiple keys map to the same position.

---

# 10. Learning Outcomes

After completing these laboratory experiments, I gained practical exposure to the following:

1. Understanding fundamental and advanced data structures.
2. Implementing recursive algorithms using Python functions.
3. Applying searching algorithms to locate elements.
4. Implementing different sorting techniques and comparing their complexities.
5. Creating and manipulating singly, doubly and circular linked lists.
6. Implementing stacks using arrays and linked lists.
7. Understanding queue operations and circular queue implementations.
8. Representing binary trees using arrays and linked lists.
9. Implementing Binary Search Trees and different traversal methods.
10. Understanding AVL tree balancing and rotation operations.
11. Implementing hashing techniques and collision resolution.
12. Handling common programming errors and debugging logical conditions.
13. Improving algorithmic thinking and problem-solving skills.

---

# 11. Error Handling and Debugging

During the laboratory exercises, different programming errors and logical issues were identified and rectified.

Some important examples include:

| Error / Issue | Rectification |
|---|---|
| RecursionError | Use appropriate base conditions |
| IndexError | Check array and list boundaries |
| Infinite Loop | Update traversal variables correctly |
| Stack Underflow | Check whether the stack is empty |
| Queue Underflow | Check whether the queue is empty |
| Incorrect Node References | Update links during insertion and deletion |
| Incorrect Tree Traversal | Follow the correct traversal sequence |
| AVL Imbalance | Apply appropriate rotations |
| Hash Collision | Use collision resolution techniques |
| ValueError | Validate user input |
| AttributeError | Check object and node references |
| IndentationError | Maintain proper Python indentation |

---

# 12. Conclusion

The Data Structures and Algorithms Laboratory provided practical experience in understanding and implementing important data structures and algorithmic techniques using Python.

Starting from recursion and basic searching algorithms, the experiments gradually progressed towards advanced sorting techniques, linked lists, stacks, queues, binary trees, Binary Search Trees, AVL trees, and hashing.

These implementations helped develop a better understanding of how data is stored, accessed, modified, searched, sorted, and organized efficiently.

The laboratory work also strengthened programming fundamentals, logical reasoning, debugging skills, and the ability to translate algorithmic concepts into working Python programs.

This repository serves as a structured collection of the implementations and practical work completed throughout the **23CSE203 – Data Structures and Algorithms Laboratory**.

---

# 13. Acknowledgement

I sincerely thank **Dr. Rajkumar Batchu**, Assistant Professor, School of Computing, Amrita Vishwa Vidyapeetham, for the guidance and support provided throughout the Data Structures and Algorithms Laboratory.

I also acknowledge the learning opportunities provided by the laboratory sessions, which helped me understand the practical implementation of data structures and algorithms.

---

## Author

**JASHTI HEMENDRA**

B.Tech – Computer Science and Engineering  
2nd Year | Semester 3 | CSE-B  
Amrita Vishwa Vidyapeetham

**Course:** Data Structures and Algorithms  
**Course Code:** 23CSE203

---

<p align="center">
  <strong>Learning Data Structures. Understanding Algorithms. Building Problem-Solving Skills.</strong>
</p>
