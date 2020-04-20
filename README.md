# CPU-Scheduling-Algorithms
This repository is an implementation of CPU Scheduling Algorithm namely:
(1)First In First Out(FIFO)
(2)Shortest Job First(SJF)-Non Preemptive
(3)Shortest Job First(SJF)-Preemptive
(4)Round Robin
This dynamically gets input from the user and schedules the process based on the scheduling algorithm chosen.
The program uses the concept of multiple threads. 
Here, different states like ready state, running state and blocked state are implemented using threads.
The inputs should be of the form <CPU burst time1, I/O time, CPU burst time2>
If the process does not have I/O time it can entered as zero, similarly for either of the CPU burst time.
Inputs must be given very large to really experience the implementation of the algorithms because the CPU burst time is reduced in the loop which runs very faster than we manually give next input.
So, taking very large numbers like 400000 as input helps us to witness the exact working of the algorithms.
