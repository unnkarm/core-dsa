Core Data Structures in C

A structured and comprehensive collection of core data structures implemented in C, written with a strong focus on conceptual clarity, correctness, and exam-oriented preparation.

This repository is designed as a foundational reference for Computer Science students preparing for DSA-heavy exams (GATE, DRDO, ISRO, university exams) and for strengthening low-level problem-solving skills.

Objectives

Build a solid understanding of core data structures

Practice clean and modular C programming

Create a personal revision-ready reference

Strengthen foundations before moving to advanced topics (OS, DBMS, Algorithms, ML)

Repository Structure
core-dsa-in-c/
│
├── arrays/
│   ├── traversal.c
│   ├── insertion.c
│   ├── deletion.c
│   ├── searching.c
│   └── sorting.c
│
├── linked-list/
│   ├── singly_ll.c
│   ├── doubly_ll.c
│   ├── circular_ll.c
│   └── ll_operations.md
│
├── stack/
│   ├── stack_array.c
│   └── stack_linkedlist.c
│
├── queue/
│   ├── simple_queue.c
│   ├── circular_queue.c
│   ├── deque.c
│   └── priority_queue.c
│
├── tree/
│   ├── binary_tree.c
│   ├── bst.c
│   ├── tree_traversals.c
│   └── tree_notes.md
│
├── heap/
│   ├── min_heap.c
│   └── max_heap.c
│
├── hash/
│   ├── hash_chaining.c
│   └── hash_open_addressing.c
│
├── graph/
│   ├── graph_representation.c
│   ├── bfs.c
│   └── dfs.c
│
├── utils/
│   └── common.h
│
└── README.md

Covered Data Structures
Linear Data Structures

Arrays

Linked Lists (Singly, Doubly, Circular)

Stack (Array & Linked List implementation)

Queue (Simple, Circular, Deque, Priority Queue)

Non-Linear Data Structures

Binary Tree

Binary Search Tree (BST)

Heap (Min Heap, Max Heap)

Graph (Adjacency List, BFS, DFS)

Hashing

Hash Table using Chaining

Hash Table using Open Addressing

Implementation Principles

Written in pure C

No unnecessary abstractions

Emphasis on:

Correct logic

Edge case handling

Readability

Each file is self-contained

Menu-driven programs where applicable

How to Run

Compile using GCC:

gcc filename.c -o output
./output


Example:

gcc stack_array.c -o stack
./stack

Intended Audience

Computer Science students

GATE / DRDO / ISRO aspirants

Anyone revisiting DSA fundamentals in C

Learners who prefer depth over hype

Learning Philosophy

This repository prioritizes understanding over shortcuts.
The goal is not competitive coding speed, but strong internalization of how data structures work at the memory and logic level.

Status

🟢 Actively maintained
🧱 Focused on foundations
📌 Designed for long-term reference

Future Extensions (Planned)

AVL Trees

Disjoint Set (Union–Find)

Tries

Time & Space Complexity notes

Advanced Graph Algorithms

Author

Unnita Karmakar
B.Tech (CSE)
Focused on strong CS fundamentals and long-term growth in core domains.
