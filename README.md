# Scheduling-OS
FCFS Scheduling-
First Come First Served (FCFS) scheduling is the scheduling algorithm which allocates CPU to the processes in the order of their arrival. This is managed by a First In First Out (FIFO) queue. It is not ideal for large workloads and responsive systems as the wait times can often be long.

Round Robin Scheduling-
Round Robin (RR) scheduling is the scheduling algorithm in which the CPU is shifted to the next process in the ready queue after a fixed amount of time known as time quantum. It is a preemptive scheduling algorithm and the preempted process is added to the end of the queue. This algorithm prevents starvation of processes.

Analysis of the performance of Scheduling algorithms for different workloads-

•	First Come First Served (FCFS) Scheduling-
FCFS scheduling is quite efficient in scheduling short processes. But, due to generally higher wait times, FCFS scheduling is not suitable for interactive processes which are I/O intensive.
C2, which is an I/O intensive process, has significantly higher waiting and turnaround times than the other processes. C1, a compute intensive process, does not experience a sizable variation in the waiting and turnaround times when the workload size is increased. C3, which is a compute and I/O intensive process, experiences a moderate increase in the waiting and turnaround times.
 
•	Round Robin (RR) Scheduling-
The primary advantage of RR Scheduling is that it does not lead to starvation and all the processes get an equal share of the resources. However, determining the time quantum is pivotal. If it is too short, there will be a lot of context switches. If it is too long, it tends towards FCFS scheduling.
The process C2 which is I/O intensive has significantly larger waiting and turnaround times than C1 and C3, when workload size is increased while C1 and C3 experience less variance.

