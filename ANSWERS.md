**1. List all of the main states a process may be in at any point in time on a standard Unix system. Briefly explain what each of these states means.**
Start - Process is first started
Ready - Process is waiting to be assigned to a processor
Running - Process has been assigned to a processor and the processor is executing the instructions
Waiting - Process is waiting for some form of data
Terminated - Process is finished executing or is terminated by the OS, it waits to be removed from memory.


**2. What is a zombie process?**
Zombies are the leftover bits of dead processes that haven’t been cleaned up properly


**3. How does a zombie process get created? How does one get destroyed?**
If the parent process doesn't wait for the child's termination and instead executes its next task, the child's exit status won't be read by the parent. This results in the creation of a zombie process.

Terminate the parent process.


**4. What are some of the benefits of working in a compiled language versus a non-compiled language? More specifically, what benefits are there to be had from taking the extra time to compile our code?**

End performance because the code gets compiled into machine code which is more efficient.