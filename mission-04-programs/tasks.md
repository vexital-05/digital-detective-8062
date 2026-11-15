# MISSION 4 - How programs run

## Task 4.1 - Create and run a Python program

#### This task is completed and the steps done to do the same are shown in this [image](../evidence/mission-04/task4.1.png)

---

## Task 4.2 - Compare compiler and interpreter

| Point | Compiler | Interpreter |
| --- | --- | --- |
| When translation / execution happens | The compiler translates the entire program into machine code before execution | The interpreter translates and executes the source code line by line during execution |
| Typical output | A compiler outputs the machine code which is then saved to the disk | The interpreter directly prints the result of the program during runtime |
| One example | GCC (GNU Compiler Collection) is the compiler which is used for C++ | CPython is the interpreter which is used for Python |
| One advantage | Since it compiles the entire program at once, it takes much lesser time to output the result | Since it executes the code line by line, it is much easier to debug the code |

#### The main difference between a compiler and an interpreter is that the compiler runs the entire code at once whereas the interpreter runs the code line by line. Due to this both the compiler and the interpreter have its own advantages and disadvantages, which can be used to understand which type of programming language should be used in which use case.