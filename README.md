# Demand Paging Simulator
This repository creates a demand paging simulator that mimics the process of loading pages into memory on-demand. The simulator should handle page faults, including distinguishing between different types of page faults. Implement a basic page replacement policy (FIFO) to manage memory frames.
### Overview
Demand paging is a memory management scheme where a page of memory is brought into the physical memory only when it is needed (on-demand) by the executing program. This is in contrast to pre-paging where pages are brought into memory in anticipation of their use. The main advantage of demand paging is that it reduces the number of pages loaded into memory at any given time, thus conserving memory resources.
### Features
- **Page Access:** Implement a method to access pages.
- **Status Printing:** After each page access, print the current status of memory frames and the count of different types of page faults.
- **Simulation:** Simulate the demand paging for a given sequence of page accesses. Print the final statistics, including the total number of page faults.
### Flow of Execution
1. **Input:** The program starts by asking the user for the number of frames and pages, followed by the page reference string.
2. **Page Replacement Algorithms:** The program runs the FIFO, Optimal, and LRU algorithms sequentially on the provided page reference string.
Each algorithm keeps track of page faults and prints the state of the frames after each page reference.
3. **Output:** The program prints the total number of page faults for each algorithm after processing the page reference string.






