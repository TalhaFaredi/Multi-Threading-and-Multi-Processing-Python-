
# Python Multithreading and Multiprocessing Examples

This repository contains various Python scripts that demonstrate the use of multithreading and multiprocessing to handle both CPU-bound and I/O-bound tasks. These examples show how to efficiently distribute tasks across threads and processes to optimize performance.

## Overview of Scripts

### 1. **Multiprocessing with ProcessPoolExecutor**
   - This script demonstrates how to use the `ProcessPoolExecutor` for running CPU-bound tasks in parallel.
   - It distributes the task of squaring numbers across multiple processes, improving performance by utilizing multiple CPU cores.
   
### 2. **Real-World Example: Multiprocessing for CPU-bound Tasks (Factorial Calculation)**
   - This script presents a real-world use case of multiprocessing for computing factorials of large numbers.
   - Factorial calculations involve substantial computational work, making them ideal candidates for parallel execution using multiprocessing.

### 3. **Basic Multiprocessing**
   - This example highlights the use of the `multiprocessing` library to run tasks in parallel on different CPU cores.
   - Two processes are created to compute squares and cubes concurrently, demonstrating the power of parallel execution for CPU-heavy tasks.

### 4. **Multithreading**
   - This script explains how to use Python's `threading` module for handling I/O-bound tasks concurrently.
   - It creates threads to print numbers and letters concurrently, improving efficiency when dealing with tasks that involve waiting for input/output operations.

### 5. **Real-World Example: Multithreading for I/O-bound Tasks (Web Scraping)**
   - In this practical example, multithreading is used to scrape multiple web pages concurrently.
   - By fetching web content in parallel, it reduces the time spent waiting for responses from servers, making the scraping process much more efficient.

### 6. **Advanced Multithreading with ThreadPoolExecutor**
   - This script introduces the `ThreadPoolExecutor` for managing a pool of threads to perform tasks concurrently.
   - Multiple numbers are printed concurrently, utilizing up to 3 worker threads. This approach simplifies thread management and boosts performance when dealing with a large number of tasks.

## Requirements

- Python 3.x
- Install necessary dependencies

## How to Run


1. Run any script of your choice:
   ```bash
   python script_name.py
   ```

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

---

