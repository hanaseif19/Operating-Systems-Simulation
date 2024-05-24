# OS Project with MLFQ Scheduling

This project implements an operating system in Java featuring Multi-Level Feedback Queue (MLFQ) scheduling. The OS is designed to handle resource and memory allocation, file reading, and concurrency using mutexes. Key features include:

## Key Features

- **MLFQ Scheduling:** Efficiently manages process execution using multiple queues with different priority levels and different quantums, ensuring fair CPU time distribution.
- **Concurrency with Mutexes:** Ensures safe access to shared resources by multiple processes, preventing race conditions and deadlocks using multiple mutexes.
- **Resource and Memory Allocation:** Dynamatically allocates resources and memory to processes, optimizing system performance and stability.
- **File Reading:** Supports reading from files, enabling processes to later be executed by interpreting the instructions through an interpreter.
- **Functions:** Supports 6 operations: `readFile`, `writeFile`, `print`, `assign`, and `printToFrom`,`semWait` and `semSignal`.

This OS project demonstrates advanced operating system concepts and is designed for educational purposes, showcasing the integration of scheduling, memory management, and concurrency control.
