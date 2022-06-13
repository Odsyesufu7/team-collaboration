# Simple Shell Project
![image](https://user-images.githubusercontent.com/102301571/173282677-62f49818-380c-4628-87ee-66e57b8fcb47.png)
# Overview
## Write a simple UNIX command interpreter.
#  Aim
## A Unix Command Line Interpreter Built in C
# General 
* Who designed and implemented the original Unix operating system?
  Answer:Ken Thompson and Dennis Ritchie created the first version of UNIX on a PDP-7 as a team in 1969.
* Who wrote the first version of the UNIX shell?
  Answer: The fisrt Unix shell was the Thompson shell, sh, written by Ken Thompson at Bell Labs and which was distribued with versions 1 through 6 of Unix, from 1971   to 1975.
* Who invented the B programming language (the direct predecessor to the C programming language)?
  Answer: B programming language was developed at Bell Labs circa 1969, by Ken Thompson and Dennis Ritchie
* Who is Ken Thompson?
  Answer: There are many meaning to who Ken Thompson is, but Kenneth Lane Thompson is an American pioneer of computer science. Thompson worked at Bell Labs for most     of his career where he designd and implemented the original Unix operating system.
* How does a shell work?
  Answer: Shell corresponds in the computer world to a command intrpreter where the usr has an available interface (CLI, Command-Line Interface), through which he has   the possibility of accessing services of the operating system as well as executing or invoking programs
* What is a pid and a ppid?
  Answer: PID stands for Process ID, which means Identification Number for currently running process in Memory. while
  PPID stands for Parent Process ID, which means Parent Process is the responsible for creating the current process(Child Process). Through Parent Process, The child   process will be created.
* How to manipulate the environment of the current process?
  Answer:You can only influence a process's environment variables at the time the process starts up.If you need to communicate a change to a running process, the       environment isn't the right tool, to perform it.
* What is the difference between a function and a system call?
  Answer: A function call is a request made by a program to perform a specific task. While
  A system call is a request for the kernel to access a resource.
* How to create processes?
  Answer: I UNIX and POSIX you call fork() and then exec() to create a process. When you fork it clones a copy of your current process, including all data, code,       environment variables, and open files. This child process is a duplicate of the parent (execept for a few details). 
* What are the three prototypes of main?
  Answer: They are, int main(); , int main(int argc, char **argv);
* How does the shell use the PATH to find the programs?
  Answer: The shell tries each directory in the PATh, left-to-right, and runs the executable program with the matchig command name that it finds
* How to execute another program with the execve system call?
  Answer: execve() executes the program pointed to by filename. filename must be either a binary executable. or a script starting with a line of the form "#!           interpreter [arg]".
  execve() does not return on success, and the text, data, bss, and stack of the calling process are overwritten by that of the program loaded.
* How to suspend the execution of a process until one of its children terminates?
  Answer: "The wait() system call" suspends execution of the current process untilone of its children terminates
* What is EOF / “end-of-file”?
  The EOF operator is used in many programming languages. This operator stands for the end of the file. This means that wherever a compiler or an interpreter           encounters this oprator, it will receive an indication that the file it was reading has ended.