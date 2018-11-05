# Demonstration-of-Linux-fork-command-using-GCC
This short program was created for the Operating Systems I course at UoPeople.

The program shows how fork can be used to generate a child process, the child will have a different PID, and the parent and child can diverge in terms of values.

The program first initializes a variable and assigns it a value.
The process id (PID) is printed for that main process.
Fork() is used to make a copy of the main process.
The values of the parent and child processes are each modified in a unique way.
The PIDs are printed along with the current value of both the parent and child processes.
