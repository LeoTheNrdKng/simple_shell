# 0x16. C - Simple Shell

## Description

A simple UNIX command-line interpreter, implemented as part of a group project for ALX School.

## Table of Contents

- [Concepts](#concepts)
- [Background Context](#background-context)
- [Important Message from Julien](#important-message-from-julien)
- [Resources](#resources)
- [Learning Objectives](#learning-objectives)
- [Requirements](#requirements)
- [Compilation](#compilation)
- [Testing](#testing)
- [Checks](#checks)
- [Tasks](#tasks)
  - [Betty would be proud](#task-0-betty-would-be-proud)
  - [Simple shell 0.1](#task-1-simple-shell-01)
  - [Simple shell 0.2](#task-2-simple-shell-02)
  - [Simple shell 0.3](#task-3-simple-shell-03)
  - [Simple shell 0.4](#task-4-simple-shell-04)
  - [Simple shell 1.0](#task-5-simple-shell-10)

## Concepts

For this project, we expect you to look at these concepts:

- Everything you need to know to start coding your own shell
- Approaching a Project

## Background Context

Write a simple UNIX command interpreter based on "The Gates of Shell," by Spencer Cheng, featuring Julien Barbier.

## Important Message from Julien

It’s time for the famous Simple Shell project. This is one of the most anticipated projects and also one that will challenge you a lot about everything you have learned so far:

- Basics of programming
- Basics of C
- Basics of thinking like an engineer
- Group work
- Learning how to learn

I would like to take this moment to remind you about a few important things:

- First, remember the framework. If you do not know it by heart already, it is probably a good idea to read it again: [Framework Link](https://intranet.alxswe.com/concepts/559)
- NEVER copy any code, never look at solutions (and never give any solution to your friends, you are not helping them by doing so)
- ALWAYS write code alone from scratch after you get help to check that you have actually understood. If you cannot do it, you have not understood enough and need to study more. Do not rewrite code from memory, but from understanding.


## Resources

Read or watch:

- Unix shell
- Thompson shell
- Ken Thompson
- Everything you need to know to start coding your own shell concept page
- man or help:
  - sh (Run sh as well)

## Learning Objectives

At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

- General
  - Who designed and implemented the original Unix operating system
  - Who wrote the first version of the UNIX shell
  - Who invented the B programming language (the direct predecessor to the C programming language)
  - Who is Ken Thompson
  - How does a shell work
  - What is a pid and a ppid
  - How to manipulate the environment of the current process
  - What is the difference between a function and a system call
  - How to create processes
  - What are the three prototypes of main
  - How does the shell use the PATH to find the programs
  - How to execute another program with the execve system call
  - How to suspend the execution of a process until one of its children terminates
  - What is EOF / "end-of-file"?

## Requirements

- Allowed editors: vi, vim, emacs
- All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89
- All your files should end with a new line
- A README.md file, at the root of the folder of the project, is mandatory
- Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl
- Your shell should not have any memory leaks
- No more than 5 functions per file
- All your header files should be include guarded
- Use system calls only when you need to (why?)
- Write a README with the description of your project
- You should have an AUTHORS file at the root of your repository, listing all individuals having contributed content to the repository.


## Compilation

Your shell will be compiled this way:

```bash
gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o hsh