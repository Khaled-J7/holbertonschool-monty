# holbertonschool-monty

C - Stacks, Queues - LIFO, FIFO

![image](https://github.com/Khaled-J7/holbertonschool-monty/assets/135613251/f5498bfb-a23b-41bd-a58e-65d988a791cf)


Description
This is a project developed as part of the Holberton School curriculum. It involves creating a simple interpreter for Monty bytecode files. The interpreter can parse Monty bytecode files, execute stack and queue operations, and handle various errors.

Monty Language
Monty is a simple language with a set of stack and queue operations. Each operation is represented by a keyword, and the interpreter reads a Monty bytecode file line by line, executing the specified operations. The project includes various Monty operations such as push, pall, pint, pop, swap, add, sub, mul, div, mod, comments, and more.

Usage
To compile the Monty interpreter, use the following command:

gcc -Wall -Werror -Wextra -pedantic *.c -o monty


To run a Monty bytecode file, use the following command:

./monty filename.m

Replace filename.m with the name of the Monty bytecode file you want to execute.

##Example
Suppose you have a Monty bytecode file named example.m with the following content:

push 1
push 2
push 3
pall

You can run it using the Monty interpreter as follows:
./monty example.m

The output will be:

3
2
1

Authors: 

This project was developed by:

Rayen Jouini
Khaled Jallouli
Khairi Taboubi
