# os-assignment
1.Write a C program priority.c that implements preemptive priority CPU
scheduling(high value has higher priority).

Preemptive Priority CPU Scheduling is a process scheduling method used in operating systems where each process is assigned a priority value. The CPU always executes the process with the highest priority, and if a new process arrives with a higher priority than the currently running one, the current process is interrupted and the CPU is given to the new process. This ensures that more important tasks are handled first. It is commonly used in systems where certain tasks need faster response, but it may lead to starvation of low-priority processes if not properly managed.
