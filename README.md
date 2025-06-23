# Multithreading Concepts Library

This project is a **practice-focused multithreading library** built on top of **POSIX threads (pthreads)**. It aims to explore and implement a wide range of **thread synchronization mechanisms**, serving as both a learning exercise and a flexible foundation for concurrent programming in C/C++.

## Purpose

The goal of this project is to **deepen understanding of multithreading concepts** by implementing them from scratch rather than relying solely on built-in primitives. Each module in the library represents a classic or advanced synchronization construct used in real-world concurrent systems.

## Features & Modules

- **Wait Queues**  
  Efficient queuing mechanism for blocked threads waiting on a condition.

- **Thread Pausing / Resuming**  
  Manual control over thread execution via signaling.

- **Thread Barriers**  
  Coordination point where multiple threads wait until all reach a barrier.

- **Monitors (Condition + Mutex)**  
  Encapsulated structure that combines mutual exclusion with condition variables.

- **Assembly Line Pattern**  
  Simulates multi-stage producer-consumer flows.

- **Event Loops**  
  Single-threaded, event-driven execution model.

- **Single-threaded Concurrency**  
  Cooperative multitasking using explicit yielding.

- **Timers**  
  Timeout-based synchronization and delayed execution.

- **Custom Read-Write Locks**  
  Allows multiple readers or one writer, designed from primitives.

- **Custom Recursive Locks**  
  Mutexes that can be re-acquired by the same thread.

- **Custom Semaphores**  
  Classic counting semaphores for managing access to limited resources.

- **Thread Pool**  
  Fixed number of reusable threads to execute queued jobs.

## Technologies

- **Language**: C (GCC)
- **Threading Library**: POSIX Threads (pthreads)
- **Build Tool**: `Make`


## Source & Attribution

This project is a **reimplementation for learning purposes**, based on the original work:  
[sachinites/MultithreadingBible](https://github.com/sachinites/MultithreadingBible)

While the codebase has been rewritten and reorganized by myself to reinforce multithreading concepts,  
the design, structure, and idea flow may closely follow the original repository.

All credit for the original idea, design patterns, and explanations goes to the original author.

