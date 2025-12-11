# adaptive-resource-allocation
🧠 Adaptive Resource Allocation in Multiprogramming Systems

This project is a C++ simulation of an adaptive operating system scheduler that dynamically adjusts CPU and memory resources among multiple processes to optimize system performance.

📘 Overview

Traditional multiprogramming systems use static CPU and memory allocation, often leading to bottlenecks or starvation.
This project introduces adaptive scheduling, which continuously monitors system metrics and reallocates resources in real-time.

⚙️ Features

Round Robin Scheduling with adaptive time quantum

Dynamic Priority Boosting for long-waiting processes

CPU & Memory Utilization Monitoring

Starvation Prevention and Bottleneck Avoidance

Console-based Visualization of Process States

Final Performance Summary Report

🧩 Technologies Used
Component	Details
Language	C++
Compiler	GCC / Code::Blocks / VS Code
Libraries	<bits/stdc++.h>, <queue>, <vector>, <iostream>
Version Control	Git + GitHub
▶️ How to Run

Clone this repository:

git clone https://github.com/<your-username>/adaptive-resource-allocation.git


Compile and run:

g++ main.cpp -o adaptive_allocation
./adaptive_allocation


Observe adaptive changes in:

CPU utilization

Memory usage

Process waiting and turnaround times

📊 Output Example
=== Starting Simulation ===
[Time 0] Running Process 0
[Adaptive] New Time Quantum: 5
Process 0 finished at time 12
CPU Utilization: 92%
Memory Utilization: 75%

🧾 Report

The full project report is available here:
📄 Adaptive_Resource_Allocation_Report.pdf

🧠 Future Enhancements

Add GUI or web-based visualization

Implement I/O-bound process handling

Introduce multi-core CPU simulation

Integrate ML-based workload prediction

👨‍💻 Author

Shikher Singh
B.Tech CSE | Lovely Professional University
📍 Jammu, India

🏷️ GitHub Topics
operating-system  cpp  scheduling-algorithm  adaptive-system
multiprogramming  cpu-scheduling  os-simulator  lpu

