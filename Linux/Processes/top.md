# TOP
## Table Of Processes
The top command shows a real-time view of running processes in Linux and kernel-managed tasks. 
It also shows a system information summary that shows CPU, memory and resource utilization.


`top`
as soon as this command is run it will display an interactive command mode.
The top half shows the statistics and resource utilization. The bottom half shows the currently running processes.
![top](/Linux/Images/top.png)

- **PID** = Unique process id
- **PR** = Process priority (lower number = higher priority)
- **VIRT** = Virtual memory used by the process
- **USER** = Username of process owner
- **%CPU** = CPU usage
- **TIME+** = CPU time
- **SHR** = Shared memory size (kb)
- **NI** = Nice Value of task. Negative represents a high priority task. Positive represents a low priority task.
- **%MEM** = Memory usage
- **RES** = How much physical RAM the program is using (kb)
- **COMMAND** = Name of the command that started the process

---
Version v1.0