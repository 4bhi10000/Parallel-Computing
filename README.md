# Parallel Matrix Multiplication using Sequential, OpenMP, MPI and CUDA

## Experiment 1 — Parallel Computing

This experiment solves the same matrix multiplication problem using four different computing approaches:

1. **Sequential CPU**
2. **OpenMP Shared-Memory Parallelism**
3. **MPI Distributed-Memory Parallelism**
4. **CUDA GPU Parallelism**

The main purpose is to observe how matrix multiplication performs under different parallel computing models and compare their execution times.

---

## Table of Contents

- [1. Objective](#1-objective)
- [2. Problem Definition](#2-problem-definition)
- [3. Experimental Environment](#3-experimental-environment)
- [4. Project Structure](#4-project-structure)
- [5. Sequential Implementation](#5-sequential-implementation)
- [6. OpenMP Implementation](#6-openmp-implementation)
- [7. MPI Implementation](#7-mpi-implementation)
- [8. CUDA Implementation](#8-cuda-implementation)
- [9. Results](#9-results)
- [10. Performance Comparison](#10-performance-comparison)
- [11. Speedup Analysis](#11-speedup-analysis)
- [12. Verification](#12-verification)
- [13. Observations](#13-observations)
- [14. Overall Comparison](#14-overall-comparison)
- [15. Conclusion](#15-conclusion)
- [Technologies Used](#technologies-used)
- [Experiment Summary](#experiment-summary)
- [Author](#author)

---

## 1. Objective

The aim of this experiment is to implement matrix multiplication using multiple computing approaches:

- Sequential execution on a CPU
- Shared-memory parallel execution using OpenMP
- Distributed-memory execution using MPI
- GPU-based parallel execution using CUDA

The experiment helps demonstrate how parallel processing can improve the execution time of computationally demanding matrix operations.

---

## 2. Problem Definition

Two square matrices are considered:

```text
A = 4000 × 4000
B = 4000 × 4000
