# CPU Scheduler Simulator (Java + Maven)

This project simulates multiple CPU scheduling algorithms under various workloads using Java. Designed for OS performance experimentation, it supports FCFS, RR, SJF, IdealSJF, and MLFQ schedulers.

## Features
- Experiment automation via batch files
- Configurable input/output structure
- CSV result aggregation for analysis
- Modular scheduler architecture in Java

## How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/cpu-scheduler-simulator.git
   cd cpu-scheduler-simulator
2. Build the project with Maven:

  bash
  Copy code
  mvn clean install
  
3. Navigate to any experimentX/ folder and run:
  ./run.bat  (Windows)
# File Structure
/src/main/java: Core simulator logic

/experiment1,2,3: Run configurations and CSV results

/docs: Report documentation

# Requirements
Java 11+

Maven 3+

Author
