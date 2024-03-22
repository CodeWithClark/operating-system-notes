## ...THE MEMORY REMAINS pt. 1

## Ch. 8 - Main Memory

- Memory consists of a large array of words or bytes, each with its own address.

- Main memory and the registers built into the processor itself are the only storage that the CPU can access directly. 
- Machine instructions take memory addresses as arguments, but no machine instruction can take disk addresses. 
  - **Any instructions** in execution, and **any data being used by the  instructions**, must be in one of these direct-access storage devices. 
  - If the data are not in memory, they must be moved there before the CPU can  operate on them.

- accessed via a transaction on the memory bus.

A processor must  **stall** when it doesn't have the data required to complete the instruction it is executing.

 - A remedy to prevent this is to <u>add fast memory between CPU and MAIN MEMORY</u>
   - A memory buffer used to accommodate a speed differential is called **cache**

- BASE REGISTR: Holds smallest legal physical memory address
- LIMIT REGISTER: specifies the size of the range
  - IF: base register holds 300040 and the limit is 120900, then the program can legally access all adresses from 300040 (+120900) through 420939 (inclusive).



![264](/home/clark/Code/notes/Operating System/Base-Base+Limit.gif)

- Since privileged instructions can be executed only in kernel mode, 
  - and  since only the operating system executes in kernel mode, 
    - <u>*only the  operating system can load the base and limit registers*</u>. 
  - the operating system can change the value of the registers but prevents user programs from changing the registers’ contents.
- 