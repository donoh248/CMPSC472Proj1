Description of the project:
The project involves a multi-threaded program that manages threads, LWPs (Lightweight Processes), processes, and inter-process communication (IPC) using shared memory and message queues.
Structure of the code with diagram and some descriptions regarding structure:

The code consists of several components:
Thread management: Creates, suspends, resumes, and terminates threads.
LWP management: Tracks LWPs associated with processes.
Process management: Tracks processes and their associated threads and LWPs.
Inter-process communication (IPC): Utilizes shared memory and message queues for communication between processes.
Evaluation of IPC performance: Measures the time taken to send messages through shared memory and message queues.
Instructions on how to use it for full functionalities provided by your code:

Run the program and follow the prompts to perform various actions such as creating threads, suspending/resuming threads, terminating threads/processes, and evaluating IPC performance.
Use the numeric options provided in the menu to select the desired action.
Verification of the sanity of the code to check the validity of the implemented functionalities:

To verify the code, perform actions such as creating threads, suspending/resuming threads, and terminating threads/processes. Check if the program behaves as expected and produces the intended output.
Evaluate IPC performance to ensure that shared memory and message queues work correctly for inter-process communication. For the screenshots I have sent them via email

Discuss your findings through this project, challenges faced during implementation, any limitations or areas for improvement:
The project held some tough challenges. It started very simply with the thread creation using the POSIX library. 
However around the parallel text filing I was unable to implement it as the program I am using does not support OpenMP Library.

Overall, the project successfully implements thread, LWP, and process management, as well as IPC using shared memory and message queues.
Challenges faced:
Understanding and implementing multi-threading concepts.
Managing synchronization and communication between threads and processes.
Debugging issues related to thread suspension, termination, and IPC.
Limitations/areas for improvement:
Better access to libraries
Enhanced user interface for better usability and clarity.
Optimization of code for improved performance and efficiency.
