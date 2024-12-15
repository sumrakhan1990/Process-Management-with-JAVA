### CPU Scheduling Algorithms Simulation

#### **Project Overview**
This project simulates CPU scheduling algorithms in Java, including **First Come First Serve (FCFS)**, **Shortest Job First (SJF)**, **Round Robin (RR)**, and **Priority Scheduling**. The simulation handles process management and provides detailed performance statistics to evaluate each algorithm's efficiency.

#### **Key Features**
- **CPU Scheduling Algorithms:** FCFS, SJF, RR, and Priority Scheduling.
- **Process File Loading:** Import process data such as IDs, arrival times, burst times, and priorities.
- **Execution & Performance Metrics:** Tracks and displays metrics such as **Completion Time (CT)**, **Turnaround Time (TAT)**, and **Waiting Time (WT)**.
- **Detailed Outputs:** Provides tabular data for each process and its metrics.

#### **Algorithms Implemented**
1. **FCFS (First Come First Serve):** Processes are executed in the order of arrival.
2. **RR (Round Robin):** Each process is assigned a fixed time quantum and executed in cycles.
3. **SJF (Shortest Job First):** Executes the shortest burst time process first.
4. **Priority Scheduling:** Processes are scheduled based on priority, with lower values indicating higher priority.

#### **System Workflow**
1. **Process Generation:** Random processes are created with unique IDs, arrival times, and burst times.
2. **User Input:** The user selects the scheduling algorithm (FCFS or RR), and if RR is selected, the time quantum is provided.
3. **Execution & Metrics Calculation:** The system calculates and displays **Completion Time (CT)**, **Turnaround Time (TAT)**, and **Waiting Time (WT)** for each process.
4. **Results:** The results are displayed in a structured table for analysis.

#### **Project Methodology**
- **Input Handling:** Processes are loaded or generated, and scheduling algorithms are selected.
- **Algorithm Implementation:** The system processes each algorithm, calculates metrics, and outputs the results.
- **Testing & Validation:** The system is tested with different numbers of processes and time quantums to ensure accuracy.

#### **Results & Conclusion**
- **FCFS:** Simple but can lead to high waiting times for late-arriving processes.
- **Round Robin:** Ensures fairness but may not be efficient for all types of workloads.
- This project serves as a valuable tool for learning about CPU scheduling and process management.

#### **Code Structure**
- **Simulator Class:** Main entry point for the simulation.
- **Schedule Class:** Implements the scheduling algorithms.
- **Statistic Class:** Calculates and displays the metrics.
- **Process Management Class:** Manages processes and their details.
- **Process Class:** Encapsulates data related to each process.

This simulation provides a hands-on approach to understanding CPU scheduling, making it an educational resource for exploring process management in operating systems.
