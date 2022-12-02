# SIMPLE SHELL PROJECT

## PROJECT DESCRIPTION

A shell is a computer program that exposes an operating system's services to a human user or other programs. In general, operating system shells use either a command-line interface (CLI) or graphical user interface (GUI), depending on a computer's role and particular operation. It is named a shell because it is the outermost layer around the operating system.
Command-line shells require the user to be familiar with commands and their calling syntax, and to understand concepts about the shell-specific scripting language (for example, bash).
Graphical shells place a low burden on beginning computer users, and are characterized as being easy to use. [Read more here](https://en.wikipedia.org/wiki/Shell_(computing))

I did the project to improve my understanding of the C language and how to the shell works in general. During the process I learnt a lot of things some of which I have listed below.

## WHAT I LEARNT


Who designed and implemented the original Unix operating system

Who wrote the first version of the UNIX shell

Who invented the B programming language (the direct predecessor to the C programming language)

Who is Ken Thompson

How does a shell work

What is a `pid` and a `ppid`

How to manipulate the environment of the current process

What is the difference between a function and a system call

How to create processes

What are the three prototypes of main

How does the shell use the `PATH` to find the programs

How to execute another program with the execve system call

How to suspend the execution of a process until one of its children terminates

What is `EOF` / “end-of-file”?


## HOW TO RUN THE PROJECT

#### LINUX

Run the line below in your command line.

NB: Make sure you are in the same folder where the simple shell project files are located.

`gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o simpleshell`

After the statement finishes running, start using your shell

`./simpleshell` 

After that line, you will be in simple shell

example command `ls` - It will list all the file in the current directory.


Please report all bugs encountered using [this issues link](https://github.com/tinotenda-alfaneti/simple_shell/issues). 

THANK YOU

