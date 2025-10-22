
CPU scheduling is the mechanism by which an operating system decides which process or thread among many ready ones gets access to the CPU next, so that the CPU doesn’t sit idle while work could be done. 

Good scheduling helps maximize CPU utilization, increase throughput (processes completed per unit time), reduce waiting time and response time, and provide fairness among processes. 

Key concepts
Arrival Time: When a process enters the ready queue. 

Burst Time: How long the process needs the CPU. 

Turnaround Time: Completion time minus arrival time. 

Waiting Time: How long a process spends waiting in the ready queue. 

Types of scheduling

Non-preemptive: Once a process starts running, it runs until it finishes or waits for I/O — no interruption by the scheduler. 
Preemptive: The OS can interrupt a running process (for example, when a higher-priority process becomes ready) and switch to another. 

Common algorithms

First-Come, First-Served (FCFS): Processes served in arrival order. 
Tutorials Point

Shortest-Job-First (SJF): Process with smallest burst time goes next. 
Tutorials Point
Round-Robin (RR): Each process gets a time slice (quantum); good for fairness in interactive systems.
