# 📘 CST1500 Coursework 2 – CPU Scheduling Algorithms
Operating Systems • C Programming • RR • FCFS

This repository contains my Coursework 2 submission for the CST1500 module.  
The assignment focuses on implementing two CPU scheduling algorithms in C:

- **First-Come, First-Served (FCFS)**
- **Round Robin (RR)**

These programs simulate how an operating system schedules processes and calculates execution times.

---

## 🧠 Overview of Algorithms

### 🔹 FCFS (First-Come, First-Served)
- Non-preemptive scheduling
- Processes are executed in the order they arrive
- Simple but can cause long waiting times
- Calculates:
  - Waiting Time
  - Turnaround Time
  - Completion Time

---

### 🔹 Round Robin (RR)
- Preemptive scheduling
- Each process gets a fixed **time quantum**
- Uses a queue to rotate processes
- Fairer execution for all processes
- Calculates:
  - Completion Time
  - Waiting Time
  - Turnaround Time
  - Execution/Gantt sequence

---

## 📁 Files Included

