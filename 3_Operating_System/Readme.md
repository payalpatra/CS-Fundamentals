### What is an Operating System?

An Operating System (OS) is software that acts as an interface between computer hardware components and the user. OS helps to communicate with the computer without knowing how to speak the computer’s language.

#### Types of Operating System :

* **Batched OS** (Example: Payroll System, Transactions Process, etc.)
* **Multi programmed OS** (Example: Windows O/S, UNIX O/S, etc.)
* **Time-Sharing OS** (Example: Multics, etc.)
* **Distributed OS** (Example: LOCUS, etc.)
* **Real-Time OS** (Example:PSOS, VRTX, etc.)
 
#### Top 10 examples of OS?
- MS-Windows
- Ubuntu
- Mac OS
- Fedora
- Solaris
- Free BSD
- Chrome OS
- CentOS
- Debian
- Android

### What are the functions of an Operating System?
Operating System controls and coordinates the use of the hardware among the various application programs for the users. The operating system acts as a resource allocator and manager. Also, the operating system is a control program that controls the user program to prevent errors and improper use of the computer. It is especially concerned with the operation and control of I/0 Devices.	<br/>						
* **Security** – The operating system uses password protection to protect user data and similar other techniques. it also prevents unauthorized access to programs and user data. <br/>	
Control over  all system health to help improve performance. records the response time between service requests and system response to have a complete view of the system health. This can help improve performance by providing important information needed to troubleshoot problems. <br/>	
* **Job accounting** – Operating system Keeps track of time and resources used by various tasks and users, this information can be used to track resource usage for a particular user or group of users. <br/>	
* **Error detecting aids** – The operating system constantly monitors the system to detect errors and avoid the malfunctioning of a computer system. 
* **Coordination between other software and users** –Operating systems also coordinate and assign interpreters, compilers, assemblers, and other software to the various users of the computer systems. <br/>	
* **Memory Management** – Main memory is fast storage and it can be accessed directly by the CPU. For a program to be executed, it should be first loaded in the main memory. An Operating System performs the following activities for memory management: It keeps track of primary memory, i.e., which bytes of memory are used by which user program. The memory addresses that have already been allocated and the memory addresses of the memory that has not yet been used. In multiprogramming, the OS decides the order in which processes are granted access to memory, and for how long. It Allocates the memory to a process when the process requests it and deallocates the memory when the process has terminated or is performing an I/O operation. <br/>	
* **Processor Management** – In a multiprogramming environment, the OS decides the order in which processes have access to the processor, and how much processing time each process has. This function of the OS is called process scheduling. An Operating System performs the following activities for processor management. 
Keeps track of the status of processes. The program which performs this task is known as a traffic controller. Allocates the CPU that is a processor to a process. De-allocates the processor when a process is no longer required. <br/>	
**Device Management** –  An OS manages device communication via their respective drivers. It performs the following activities for device management. Keeping track of all devices connected to the system designates a program responsible for every device known as the Input/Output controller. Decides which process gets access to a certain device and for how long. Allocates devices in an effective and efficient way. Deallocates devices when they are no longer required. <br/>	
* **File Management** – A file system is organized into directories for efficient or easy navigation and usage. These directories may contain other directories and other files. An Operating System carries out the following file management activities. It keeps track of where information is stored, user access settings and status of every file, and more. These facilities are collectively known as the file system.

### What is Thread?

A thread is a single sequential flow of execution of tasks of a process so it is also known as a thread of execution or thread of control.

### What is a Program?

A program is a set of instructions designed to complete a specific task.

### What is Process?

Process means any program is in execution

### What is a Process Control Block?

Process Control Block(PCB) contains information about processes. For example process priority, process id, process state, etc.

### What is the difference between main memory and secondary memory?

**Main memory** - The main memory in a computer is RAM (Random Access Memory). It is also known as primary memory or read-write memory or internal memory. The programs and data that the CPU requires during the execution of a program are stored in this memory. <br/>
**Secondary memory** - Secondary memory in a computer is a storage device that can store data and programs. It is also known as external memory or additional memory or backup memory or auxiliary memory. Such storage devices are capable of storing high-volume data. Storage devices can be hard drives, USB flash drives, CDs, etc.

### Difference between Process and Thread?

**Multiprogramming** – A computer running more than one program at a time (like running Excel and Firefox simultaneously). 
**Multiprocessing** – A computer using more than one CPU at a time. 
Ex - UNIX Operating system
**Multitasking** – Tasks sharing a common resource (like 1 CPU)
Ex - Responding to emails while listening to a podcast.

### Difference between multitasking and multiprogramming?

Sl | Multiprogramming  | Multi-tasking     | 
--- | --- | --- | 
1 |The concept of Context Switching is used.| The concept of Context Switching and Time Sharing is used.|
2 |In a multiprogramming system, the operating system simply switches to, and executes, another job when the current job needs to wait.  |The processor is typically used in time-sharing mode. Switching happens when either allowed time expires or where there is another reason the current process needs to wait (for example a process needs to do IO).|
3 |Multiprogramming increases CPU utilization by organizing jobs.|In multi-tasking also increases CPU utilization, it also increases responsiveness.|
4 |The idea is to reduce the CPU idle time for as long as possible. |The idea is to further extend the CPU Utilization concept by increasing responsiveness Time Sharing.|

### Difference between Process and Program?

A program and a process are related terms. The major difference between program and process is that a program is a group of instructions to carry out a specified task whereas the process is a program in execution. While a process is an active entity, a program is considered to be a passive one.

### What is multithreading?

Multithreading refers to a process of executing two or more threads simultaneously for maximum utilization of the CPU.

### What is CPU scheduling?

CPU Scheduling is a process of determining which process will own the CPU for execution while another process is on hold. The main task of CPU scheduling is to make sure that whenever the CPU remains idle, the OS at least selects one of the processes available in the ready queue for execution.
#### Important CPU scheduling Terminologies
* **Burst Time/Execution Time** - It is the time required by the process to complete execution. It is also called running time. <br/>
**Waiting time** - Waiting time is an amount that a specific process needs to wait in the ready queue.<br/>
* **Arrival Time** - when a process enters in a ready state.<br/>
* **Finish Time** - when the process is complete and exits from a system.<br/>
* **Multiprogramming** - A number of programs that can be present in memory at the same time.<br/>
* **Jobs** - It is a type of program without any kind of user interaction.<br/>
* **User** - It is a kind of program having user interaction.<br/>
* **Process** - It is the reference that is used for both job and user.<br/>
CPU/IO burst cycle Characterizes process execution, which alternates between CPU and I/O activity. CPU times are usually shorter than the time of I/O.
* **Throughput** - The number of processes that finish their execution per unit time is known Throughput.<br/>
* **Response time** - It is the amount of time in which the request was submitted until the first response is produced.<br/>
* **Turnaround Time** - Turnaround time is the amount of time to execute a specific process. It is the calculation of the total time spent waiting to get into the memory, waiting in the queue and executing on the CPU. The period between the time of process submission to the completion time is the turnaround time.<br/>
* **Preemptive** - Preemption as used with respect to operating systems means the ability of the operating system to preempt (that is, stop or pause) a currently scheduled task in favour of a higher priority task
State of process Click. <br/>

#### State of process

* **New** – In this step, the process is about to be created but not yet created, it is the program which is present in secondary memory that will be picked up by OS to create the process.<br />
* **Ready** – Ready to run. After the creation of a process, the process enters the ready state i.e. the process is loaded into the main memory. The process here is ready to run and is waiting to get the CPU time for its execution. Processes that are ready for execution by the CPU are maintained in a queue for ready processes.<br />
* **Run** – The process is chosen by CPU for execution and the instructions within the process are executed by any one of the available CPU cores.<br />
* **Blocked or wait** – Whenever the process requests access to I/O or needs input from the user or needs access to a critical region(the lock for which is already acquired) it enters the blocked or wait state. The process continues to wait in the main memory and does not require CPU. Once the I/O operation is completed the process goes to the ready state.<br />
* **Terminated or completed** – Process is killed as well as PCB is deleted.<br />
* **Suspend ready** – Process that was initially in the ready state but were swapped out of main memory(refer Virtual Memory topic) and placed onto external storage by scheduler are said to be in suspend ready state. The process will transition back to ready state whenever the process is again brought onto the main memory.<br />
* **Suspend wait or suspend blocked** – Similar to suspend ready but uses the process which was performing I/O operation and lack of main memory caused them to move to secondary memory.

#### Types of CPU scheduling Algorithm
There are mainly six types of process scheduling algorithms: 

* **First Come First Serve  (FCFS)** - It simply schedules the jobs according to their arrival time. The job which comes first in the ready queue will get the CPU first. The lesser the arrival time of the job, the sooner the job will get the CPU.<br />
* **Shortest-Job-First (SJF)** - Shortest Job First (SJF) is an algorithm in which the process having the smallest execution time is chosen for the next execution.<br />
* **Priority Scheduling** - The processes with higher priority should be carried out first, whereas jobs with equal priorities are carried out on a round-robin or FCFS basis.<br />
* **Round Robin Scheduling** -  Round Robin is a CPU scheduling algorithm where each process is assigned a fixed time slot in a cyclic way.
Multilevel Queue Scheduling - A multi-level queue scheduling algorithm partitions the ready queue into several separate queues. <br />

### What are Deadlock and its types?

A deadlock is a condition where two or more transactions are waiting indefinitely for one another to give up locks.

### Difference between primitive and non-primitive in OS?
Sl | Preemitive  | Non- Preemptive | 
--- | --- | --- | 
Basic |	In this resources(CPU Cycle) are allocated to a process for a limited time.| Once resources(CPU Cycle) are allocated to a process, the process holds it till it completes its burst time or switches to waiting state.|
Interrupt |Process can be interrupted in between. |Process can not be interrupted until it terminates itself or its time is up.|
Starvation |If a process having high priority frequently arrives in the ready queue, a low priority process may starve.|If a process with a long burst time is running CPU, then later coming process with less CPU burst time may starve.|
Overhead |	It has overheads of scheduling the processes. | It does not have overheads.|
Flexibility| Flexible | Rigid |
Cost	| associated	| no cost associated

### Difference between Kernel and OS?
* **Kernel** - Kernel is a system program that controls all programs running on the computer. The kernel is basically a bridge between the software and the hardware of the system.

* **Operating System** - Operating system is a system program that runs on the computer to provide an interface to the computer user so that they can easily operate on the computer.

### Write the difference between microkernel and monolithic kernel?

* **MicroKernel** - It is a minimal OS that executes only important functions of the OS. It only contains a near-minimum number of features and functions that are required to implement an OS0. Example: QNX, Mac OS X, K42, etc.

* **Monolithic Kernel** - It is an OS architecture that supports all basic features of computer components such as resource management, memory, file, etc. Example: Solaris, DOS, OpenVMS, Linux, etc.

### What is paging in the operating system?

In Operating Systems, Paging is a storage mechanism used to retrieve processes from the secondary storage into the main memory in the form of pages
