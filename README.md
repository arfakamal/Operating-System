# Operating System

A collection of **Operating System laboratory programs implemented in C**, covering fundamental concepts such as process management, system calls, file handling, CPU scheduling, memory management, page replacement, disk scheduling, and process synchronization.

## 📌 Programs

### 🔹 Process Management

* **fork_exec_wait.c** – Demonstrates process creation using `fork()`, execution using `execlp()`, and synchronization using `wait()`.

### 🔹 File Handling

* **file_copy_system_calls.c** – Performs file copying using system calls such as `open()`, `read()`, `write()`, and `close()`.

### 🔹 CPU Scheduling

* **fcfs_scheduling.c** – Implements the First Come First Serve (FCFS) CPU scheduling algorithm.
* **sjf_scheduling.c** – Implements the Shortest Job First (SJF) CPU scheduling algorithm.
* **RoundRobinCPU_Scheduling.c** – Implements the Round Robin CPU scheduling algorithm using Time Quantum, Arrival Time, and Burst Time.
* **PriorityCPUScheduling.c** – Implements Non-Preemptive Priority CPU Scheduling with Arrival Time, Burst Time, and Priority.

### 🔹 Process Synchronization

* **ProducerConsumerUsingSemaphores.c** – Implements the Producer-Consumer problem using POSIX threads, semaphores, and mutex synchronization.
* **dining_philosophers.c** – Implements the Dining Philosophers problem using POSIX threads and semaphores to demonstrate synchronization and deadlock prevention.

### 🔹 Deadlock Avoidance

* **bankers_algorithm.c** – Implements the Banker's Algorithm to determine whether the system is in a safe state and handles resource requests safely.

### 🔹 Memory Management

* **memory_allocation.c** – Implements First Fit, Best Fit, and Worst Fit memory allocation strategies.

### 🔹 Page Replacement

* **page_replacement.c** – Implements FIFO, LRU, and Optimal page replacement algorithms and calculates the total number of page faults.

### 🔹 Disk Scheduling

* **disk_scheduling.c** – Implements SSTF, SCAN, and C-SCAN disk scheduling algorithms and calculates total head movement.

---

## 🛠️ Concepts Covered

* Process Creation and Management
* `fork()`, `exec()`, and `wait()` System Calls
* File Handling using System Calls
* Process Synchronization
* Semaphores
* Mutex
* POSIX Threads
* Dining Philosophers Problem
* Producer-Consumer Problem
* Deadlock Avoidance
* Banker's Algorithm
* CPU Scheduling Algorithms
* FCFS Scheduling
* SJF Scheduling
* Round Robin Scheduling
* Priority Scheduling
* Memory Allocation
* First Fit
* Best Fit
* Worst Fit
* Page Replacement Algorithms
* FIFO Page Replacement
* LRU Page Replacement
* Optimal Page Replacement
* Disk Scheduling Algorithms
* SSTF
* SCAN
* C-SCAN
* Waiting Time
* Turnaround Time
* Arrival Time
* Burst Time
* Time Quantum
* Head Movement

---

## 💻 Technology

**Programming Language:** C

**Libraries / Concepts Used:**

- Standard C Library
- POSIX Threads
- Semaphores
- Mutex
- System Calls
- Dynamic Memory and Process Management

---

## 🎯 Purpose

This repository contains my **Operating System laboratory exercises** developed to understand and implement fundamental Operating System concepts through practical C programming.

The programs focus on:

- Process management
- Process synchronization
- Deadlock avoidance
- File operations
- CPU scheduling
- Memory allocation
- Page replacement
- Disk scheduling

---

## 📚 Learning Outcomes

Through these programs, I gained practical understanding of:

- How processes are created and managed
- How system calls work in Linux
- How files can be handled using system calls
- How CPU scheduling algorithms work
- How waiting time and turnaround time are calculated
- How memory allocation strategies work
- How page replacement algorithms manage memory
- How disk scheduling algorithms reduce head movement
- How deadlocks can be avoided using Banker's Algorithm
- How synchronization is achieved using semaphores and mutexes
- How multithreading can be implemented using POSIX threads

---

## 👩‍💻 Author

**Arfa K**

B.E. CSE (Artificial Intelligence and Machine Learning)
