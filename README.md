## 🚀 Live Demo

👉 [Click here to open the Live Demo](https://weathered-wave-756.linkyhost.com)
# Multicore CPU Parallel Processing Simulator

A browser-based mini project demonstrating **parallel processing and multicore CPU scheduling**.

## Project idea

The simulator models an OS scheduler distributing independent tasks across multiple CPU cores. It lets the user change:

- Number of CPU cores
- Number of tasks
- Duration of each task

It then displays the task queue, core activity, execution timeline, CPU utilization, elapsed time and estimated speedup.

## Concepts demonstrated

1. Single-core vs multicore execution
2. Parallel task execution
3. OS scheduling
4. CPU core utilization
5. Execution timeline
6. Speedup calculation
7. Real-world motivation for multicore processors

## How to run

No installation is required.

1. Download or clone this repository.
2. Open `index.html` in Chrome, Edge or Firefox.
3. Select the number of cores and tasks.
4. Click **Start Simulation**.

## Speedup

The project estimates single-core execution time as:

`Single-core time = Number of tasks × Task duration`

Measured multicore speedup:

`Speedup = Single-core time ÷ Multicore time`

The result is educational rather than a benchmark of real CPU hardware.

## Suggested mini-project title

**"Design and Implementation of a Multicore CPU Parallel Processing Simulator"**

## Suggested viva points

- A CPU core is an independent processing unit.
- Multicore CPUs can execute independent tasks concurrently.
- The operating system scheduler assigns work to available cores.
- L1 cache is generally private to a core, while higher-level cache may be shared depending on CPU architecture.
- More cores can improve throughput, but speedup is not always linear because of synchronization, communication, memory limits and serial portions of a program.

## Files

- `index.html` – user interface
- `style.css` – design
- `script.js` – scheduler and simulation logic
- `README.md` – project documentation
