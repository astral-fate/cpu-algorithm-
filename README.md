# cpu-algorithm-

• Describe various CPU scheduling algorithms.
two classes of policies:
1.	nonpreemptive algorithms: algorithms allow a process to run to completion once it obtains the processor

2.	preemptive algorithms: preemptive algorithms use the interval timer and scheduler to interrupt a running process to real-locate the CPU to a higher-priority ready process.

• Assess CPU scheduling algorithms based on scheduling criteria. 
Maximizing CPU utilization under the constraint that the maximum response time is 300 milliseconds

Maximizing throughput such that turnaround time is (on average) linearly proportional to total execution time
• Explain the issues related to multiprocessor and multicore scheduling. 
indefinite blocking, or starvation
scheduling issues

• Describe various real-time scheduling algorithms. 

Soft real-time systems/ provide no guarantee as to when a critical real-time process will be scheduled. They guarantee only that the process will be given preference over noncritical processes.

hard real-time systems/ have stricter requirements. A task must be serviced by its deadline; service after the deadline has expired is the same as no service at all.







• Describe the scheduling algorithms used in the Windows, Linux, and Solaris operating systems. 
Dispatcher/ The Windows scheduler ensures that the highest-priority thread will always run. The portion of the Windows kernel that handles scheduling is called the dispatcher.

scheduling classes/ scheduling in the Linux system is based on scheduling classes. Each class is assigned a specific priority. By using different scheduling classes, the kernel can accommodate different scheduling algorithms based on the needs of the system and its processes. 
Solaris: uses six scheduling classes relate to one another and how they map to global priorities. Notice that the kernel maintains ten threads for servicing interrupts.


• Apply modeling and simulations to evaluate CPU scheduling algorithms.
 
Deterministic Modeling => analytic evaluation.
Queueing Models => queueing-network analysis
Simulations => race files


• Design a program that implements several different CPU scheduling algorithms

scheduling classes/ scheduling in the Linux system is based on scheduling classes. Each class is assigned a specific priority. By using different scheduling classes, the kernel can accommodate different scheduling algorithms based on the needs of the system and its processes

