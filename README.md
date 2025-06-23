# CPU Scheduling Algorithm Simulator

[Live Website](https://tejassharma.github.io/CPUScheduler/)

---

## Overview
This web-based simulator visualizes how different CPU scheduling algorithms work. Users can input process data and instantly see scheduling results like Gantt charts, average waiting time, and turnaround time. The project implements core scheduling algorithms including:
- **First Come First Serve (FCFS)**
- **Shortest Job First (SJF)**
- **Priority Scheduling**
- **Round Robin (RR)**
- **Shortest Remaining Time First (SRTF)**

---

## Features
- **Interactive Input:** Enter process details (arrival time, burst time, priority, time quantum) via a user-friendly interface.
- **Visualization:** Real-time Gantt chart and tabular output for each algorithm.
- **Performance Metrics:** Displays average waiting time, turnaround time, and more.
- **Algorithm Comparison:** Easily switch between algorithms to compare their effects.
- **Responsive Design:** Works on desktop and mobile browsers.

---

## Getting Started

### 1. Clone the Repository
```sh
git clone https://github.com/TejasHorizoN/Cpu-Scheduling-Algorithm-Simulator.git
cd Cpu-Scheduling-Algorithm-Simulator
```

### 2. Open the Simulator
Open `index.html` in your web browser, or deploy the project using GitHub Pages for online access.

---

## Usage
1. **Select an Algorithm:** Choose from FCFS, SJF, Priority, RR, or SRTF.
2. **Input Process Data:** Enter the number of processes and their details.
3. **Visualize:** Click 'Simulate' to view the Gantt chart and results.
4. **Compare:** Switch algorithms to see how results differ.

---

## Algorithms Implemented
- **FCFS:** Non-preemptive, processes served in order of arrival.
- **SJF:** Non-preemptive, shortest burst time first.
- **Priority:** Non-preemptive, based on user-assigned priority.
- **Round Robin:** Preemptive, uses time quantum for context switching.
- **SRTF:** Preemptive, shortest remaining burst time first.

---

## Screenshots
![Gantt Chart Example](images/CPU%20Scheduling_3.PNG)

---

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to your branch (`git push origin feature-branch`)
5. Open a Pull Request

---


## Author
- [Tejas Sharma](https://github.com/tejassharma)

---

## Useful Links
- [Live Demo](https://tejassharma.github.io/CPUScheduler/)
- [GitHub Repository](https://github.com/TejasHorizoN/Cpu-Scheduling-Algorithm-Simulator)



