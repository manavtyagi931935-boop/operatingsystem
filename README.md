readme_content = """# Operating Systems Lab Assignment

## Student Profile
- **Name:** Manav Tyagi
- **Course:** B.Tech (Computer Science & Engineering) — Third Year
- **Subject:** Operating Systems (CEC301)
- **Task:** Practical File and Algorithm Assignments

---

## Table of Contents
1. **Program 1:** Windows/Linux System Calls (Process Creation with parent-child tracking using fork simulation)
2. **Program 2:** Multi-threading using POSIX Threads API
3. **Program 3:** CPU Scheduling Algorithms (FCFS, Non-preemptive SJF, Non-preemptive Priority, and Round Robin)
4. **Program 4:** Process Synchronization (Producer-Consumer using Semaphores and Mutexes)
5. **Program 5:** Readers-Writers Problem using Lock Synchronizations
6. **Program 6:** Dining Philosophers Problem with Deadlock Avoidance
7. **Program 7:** Deadlock Avoidance using Banker's Algorithm
8. **Program 8:** Contiguous Memory Allocation (First Fit simulation)
9. **Program 9:** FIFO Page Replacement Algorithm
10. **Program 10:** SSTF Disk Scheduling Algorithm
11. **Program 11:** File Allocation Methods (Indexed Allocation simulation)
"""

with open("README.md", "w") as f:
    f.write(readme_content)

print("README.md has been successfully updated with the student profile and Table of Contents.")
