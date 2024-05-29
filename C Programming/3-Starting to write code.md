# Starting to Write Code

## Building and Compiling Programs

A C program, when compiled, involves compiling each source file. Programs can contain thousands of C source files. Once you compile all these files, object files are created. These object files are then linked together to create a single executable.

### Build Process

The build process involves compiling all source files and linking them. The output will show both compilation and linking steps. Building simplifies the process by combining both steps (compiling and linking) into one command.

## Compiler Errors

Compiler errors can come in two forms: syntax errors and semantic errors.

### Syntax Errors

A syntax error occurs when there is an issue with the structure of the code. This means that the code does not follow the language's syntax rules.

### Semantic Errors

Semantic errors are related to the meaning or intent of the code. These errors occur when the logic of the code is incorrect, even if the structure is syntactically correct. For example, adding two variables of different types that shouldn't be added together can lead to a semantic error.


## Linker Errors

Linker errors occur when the linker is trying to put all the pieces of a program together to create
an executable and one or more pieces are missing.

Typically, this can happen when an object file or libraries can't be found by the linker.


## Runtime Errors

Runtime errors are errors that happen when the program is executing.
These types of errors can be difficult to predict when we're writing our program.
These errors include divide by zero errors, file not found errors out of memory errors and many, many
more.

Some runtime errors can cause your program to crash.
## Logic Errors

Logic errors are errors or bugs in your code that cause your program to run incorrectly.

Logic errors are mistakes made by a programmer.

Sometimes the mistakes are careless.
Other times the mistakes are because the programmers have incomplete or incorrect information.

### Structure of a C program

- include statements #include <stdio.h>
- function main()
- {bloc of code}
- return statement 

