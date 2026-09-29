# ENCS3390 – Operating System Programming 

## Project Overview

This repository contains **Programming Task 2** for the **ENCS3390 – Operating System Concepts** course.

The project simulates a CPU scheduling system combined with resource management, deadlock detection, and recovery.

The simulation uses a single CPU core and multiple resource types with multiple instances of each resource.

## Main Features

### CPU Scheduling

The project implements:

* Preemptive Priority Scheduling
* Round Robin scheduling for processes with equal priority
* Priority aging
* Ready Queue management
* Waiting Queue management
* CPU and I/O burst simulation

### Aging

The simulation tracks how long each process remains in the Ready Queue.

If a process waits for 10 time units, its priority is improved by decreasing its priority value by 1, where a lower priority number represents a higher priority.

### Deadlock Detection and Recovery

The system monitors resource allocation and process requests to detect deadlock situations.

When a deadlock is detected, a recovery strategy is applied to resolve the deadlock and allow the simulation to continue.

## Resource Management

The simulation supports:

* Multiple resource types
* Multiple instances of each resource
* Resource requests
* Resource releases
* Waiting processes when requested resources are unavailable
* Resource allocation tracking

## Process Simulation

Each process contains:

* Process ID (PID)
* Arrival Time
* Priority
* CPU Bursts
* I/O Bursts
* Resource Requests
* Resource Releases

I/O operations are simulated independently, allowing multiple processes to perform I/O simultaneously.

## Output

The simulation provides:

* Gantt Chart
* Average Waiting Time
* Average Turnaround Time
* Detected Deadlock States
* Deadlock Recovery Information
* Process execution results

## Testing

The project was tested using different scenarios, including:

* Normal execution without deadlock
* Deadlock detection and recovery
* Multiple processes and CPU bursts
* Multiple resource requests
* Resource allocation and release
* Starvation and aging scenarios

The submitted test cases include complex scenarios with multiple processes and resource interactions.

## Technologies

* Python
* CPU Scheduling Algorithms
* Deadlock Detection and Recovery
* Resource Management
* Process Scheduling
* Operating System Concepts

## Project Structure

The repository contains the source code, input scenarios, and representative output screenshots used to test the simulation.

## Course

**ENCS3390 – Operating System Concepts**

