- Demand paging is a process of swapping in the virtual memory system.

- Not all data is moved from the hard drive to main memory at once.

- Data (pages) are transferred to main memory only when they are requested by a program.

- If the required data is already in memory, it is not copied again.

- Demand paging involves swapping data from auxiliary storage to primary memory only as needed.

- This technique is called "Lazy Evaluation" because pages are loaded only when demanded. explain this bullet points

Certainly! Here’s an explanation for each bullet point:


Demand paging is a process of swapping in the virtual memory system.

This means demand paging is used as part of virtual memory management, where parts of a program are loaded into memory from disk (swapped in) only as they are needed.

Not all data is moved from the hard drive to main memory at once.

Instead of loading the entire program/data into memory at the start, only the necessary portions are brought in. This saves memory and improves efficiency.

Data (pages) are transferred to main memory only when they are requested by a program.

When a running program tries to access something that is not currently in memory, the specific portion (called a "page") it needs is loaded at that moment.

If the required data is already in memory, it is not copied again.

If a program requests information that is already present in the main memory, the operating system does not reload or duplicate it, avoiding unnecessary
 
work.

Demand paging involves swapping data from auxiliary storage to primary memory only as needed.

"Auxiliary storage" is typically the hard disk or SSD, and "primary memory" is RAM. Demand paging moves data from storage to RAM only when the program

actually needs it.

This technique is called "Lazy Evaluation" because pages are loaded only when demanded.

The term "lazy evaluation" refers to postponing actions until absolutely necessary. In demand paging, this means only loading pages into memory when the

program requests them, not before.

Let me know if you’d like an example or further details!