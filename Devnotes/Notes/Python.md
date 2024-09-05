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
**Pseudocode** is English like statements that describe the steps in a program or algorithm
**String** is a data type that can store a literal string as a value
**Literal String** is a series of characters that are combined together and enclosed in quotes

#### Steps to understanding a problem to build a program for
- 1 Define the goal or purpose of program 2 Break down problem into smallest possible steps needed to perform tasks 3 Ensure logic and syntax (rational and instructions) are correct and in the proper order 4 What items can be stored as variables? 5 what is the logic behind sequence of steps 6 Add the use of conditions (if this, than that)
- There may be scenarios where we have conditions of branching of decisions based on user input or ther variables. For example, are you hungry has one path if you are hungry and another path of statements if you are not. 
- Other elements to consider include the ability for certain statements to run more than once. So we'd need repetition or to break down those statements into subparts of a program.

#### Forming an Algorithm
**Algorithm** is the logical step by step plan needed to solve a problem. It hass a finite number of instructions. Think big picture and whats the final goal. Consider other aspects like how often the program is meant to run, when creation deadline is, and how complex problem is. A program meant to run once can be less optimized then a program meant to run a million times a day which would need to be fully optimized.

- After understanding the problem or big picture, we can move on to individual stages and steps and how to break them down. 1 What are the **Inputs** into the problem and where are they coming from 2 What's the output of the problem or what should the end result be. 3 What is the order of the steps? order is important because it helps define the actions that need to occur. 4 Within the program, what types of decisions need to be made? This adds a layer of choice and options based on the input and other variables. 5 Are there any areas of the problem that could be repeated? Look for patterns in the algorithm. Patterns can reduce the number of steps it takes to get to your expected solution and it can be converted to code later to help with processes that need to be repeated, which streamlines the code with the use of loops, functions, classes, and methods.
-Optimize code by finding repeating patterns.

**Comment lines** are identified with a hashtag (#). Add the comment before the code, so anyone looking at your code can identify the intention of that section of code. For comments spanning multiple lines, start each new line with a hashtag. Programmers may use the # to temporarily remove lines if certain parts of code aren't functioning and needs to be tested further. It's good practice to include some details about the program in your comments at the top of the doc like your name, when it was created, and what the program is for.
#Author: 
#Created Date:
#Description:
#Example of usage:
#Result:
**Module** Self contained piece of code that can be used in different programs.
**Integrated Developmennt Environment (IDE)** ia a text editor that has additional functionality to allow developers to perform some additional tasks to simplify workflow of the development process

## 8/21/24
### From Sophia Class
**Libraries** Prewritten code collections that you can use when developing a program.
**Syntax Error** Violated the "grammar" rules of python. Replit tries to pinpoint what line the error is in, but its not always perfect. So think of it as a starting point. It also informs you what the potential errors are, just copy it into Google to learn more. With multiple errors always fix the error from top down. Quotes wrap around the literal string or python will read it as a variable or another keyword. 

## 9/4/24
### From Sophia Class
- The command **print()** is a function that allows Python to output data to the console (screen). Inside of the brackets, we have a string enclosed in double-quotes. The quotes can be single or double, but they must be the same, otherwise you will get an error.
- A red squiggly line under parts of code indicate a syntax error. Python does its best to point to the line and character it first notices an error, it may not always be correct but its a good place to start
- In the output console, you will also see more details about which file and line the error is on. In the code editor, you should see the line numbers to the left of the code. It’s important to note that these numbers are not part of the code
- With any error message, if you’re unsure of what it means, you can always copy it into Google to learn what the potential issue(s) could be. This is a good step to follow if you’re not sure about what the error represents for any programming language.
- If you see multiple errors (which is quite common in larger programs), you should fix the issues from the top down. In many instances, an issue at the top of the error list could seemingly show that there are many more errors than there really are. Don’t worry about the number of errors; put your focus on the first one.
- Developers may also use the # to temporarily remove lines. There may be certain parts of the code that aren’t functioning and need to be tested further.
**Edge cases** are values that are at the end of a testing range.
**interior tests** are test values that are within a specific range where the precise values that we entered within that range did not matter.
**corner case** is when the value you are testing is in between two edge cases.