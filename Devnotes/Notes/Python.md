# Python Notes

## 8/20/24 

### from Sophia Class
- In all programmin languages, variables cannot contain any embedded cpaces
- Python is considered an interpreted language, an it's possible to write a compiler for it. But Python is different from compiled languages like C and C++ because Python code doesn't need to be built and linked
**Program** a sequence of computer language statements that have been crafted to do something. It consists of lines of codes the computer runs and uses variables to perform them. Things must run in a specific order.
- There are three main operations executed in a program 1. **Input** to the program allows data to be entered in through a variety of ways like keyboard, mouse, file, other devices, images, sound. Input is stored into the memory and includes all types of data, like text and numeric values. 2. **Processing** data includes storing, using for calculations, validating, and sorting. 3. **Output** after processing, is sent to the monitor, printer, email, file, report, or anything we can see the resulting data.
- So input raw data, process it into useful info and then output it to the user.
**Syntax** is grammer rules of a programming language. Each programming language has it's own syntax and computers can't understand a program if the syntax is incorrect.
**Compiler** scans an entire program, aka readable code and attempts to convert the whole program at once to machine code or computer readable code. A compiled program has limitations because it can only be run on the specicic platforms it was written for.
**Machine code** aka machine language, uses binary (0&1) to perform tasks, Programming language code gets compiled to machine code.
**Bytecode** is a low level set of instructions. An intermediary step for codeconversion between programminng code and machine code
- Python is written as a .py file and when it's compiled into bytecode, it's saved as a .pyc or .pyo format
**Interpreter** takes the bytecode one line at a time and converts it to machine code. It must be installed on the computer and run through **virtual machine** a software program that behaves like a completely seperate computer within an application. Interpreted languages are preferred because they are platform independant, so as long as the bytecode and the virtual machine have the same version, a Python program can be run on any platform like Windows, MacOS, or Linux System. There are differences in how compilers and interpreters function, but the core purpose is the same with interpreters having that added step.
**Development Life Cycle** is a high level process for planning, creating, testing, and deploying an application.
-Important to understand steps in logical order 1. What problem is being asked? 2. Plan out logic for the problem by breaking it down into a sequence of steps or **algorithm** 3. Write the code to perform the algorithm 4. compile/translate the code to a format the computer can read 5. test the program to ensure theres no syntax or logical errors 6. deploy the program to be used 7. support the maintenance of the program
- Logical errors are issues the computer wouldn't catch because they are logically correct for example, you enter 100 when you meant 10. The onyl way to find these errors is to test thhe code.
syntax errors are caught by the computer in step 4.
**Variable** a location in memory where the value that's storedin that location can hold different values at various points throughout the program. Any potential user input or a result of a calculation could be a variable that could be defined and used. We want to define variables so that late on in the code we know what it references. No spaces.
- what is the logic behind sequesnce of steps? There may be scenarios where we have conditions of branching of decisions based on user input or ther variables. For example, are you hungry has one path if you are hungry and another path of statements if you are not. 
- Other elements to consider include the ability for certain statements to run more than once. So we'd need repetition or to break down those statements into subparts of a program.
**Pseudocode** is English like statements that describe the steps in a program or algorithm
**String** is a data type that can store a literal string as a value
**Literal String** is a series of characters that are combined together and enclosed in quotes

#### Forming an Algorithm
**Algorithm** is the logical step by step plan needed to solve a problem. It hass a finite number of instructions. Think big picture and whats the final goal. Consider other aspects like how often the program is meant to run, when creation deadline is, and how complex problem is. A program meant to run once can be less optimized then a program meant to run a million times a day which would need to be fully optimized.