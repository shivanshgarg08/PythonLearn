Introduction to Programming:
Programming is the process of giving computer a precise , step -by-step instructions to solve a problem.
The code is just a language to express those instructions to the computer.
Humans can infer many steps but machines or computer cannot ex_ for making a tea, we must specify all the steps explicitely and precise like taking a kettle, boiling water, adding tea and sugar, etc

#The Programming Cycle:
Every program follows a similar flow-

Problem
   ↓
Understand
   ↓
Break into steps
   ↓
Write code
   ↓
Run
   ↓
Observe output
   ↓
Debug
   ↓
Improve

# Python Programming +:
Python is a high level, Interpreted , dynamically typed programming language. It is very popular for beginners due to its simple syntax and easy to learn nature.

# Key Features:
1. Simple and readable syntax:
2. Large standard library:
3. Dynamic typing: means variable value can be changed while writing code. wheter the variable name is same/fiff
4. Platform independent: can run on all OS like mac, linux, windows
5. Large and active community:
6. Extensive third party libraries : Like numpy, Pandas, Matplotlib

#How python Executes the code: 
You write:

hello.py

        │
        ▼
Python Interpreter
        │
        ▼
Executes code line by line
        │
        ▼
Output / Error

Python reads your code from top to bottom (unless control flow changes that order with things like functions, loops, or conditionals).

#The Three types of errors:
1. Syntax Error: when code violates the rules of the programming language.
if True
    print("Hello")
    #Will show syntax error as expected ':' in line 1
python stops before running as it can't understand the syntax.

2. Runtime Error: when code is syntactically correct but causes an error during execution.
num1 = 10
num2 = 0
print(num1/num2)
#Will show runtime error as division by zero is not allowed.
This raises a ZeroDivisionError. program will run smoothly until it hits this line

3. Logical Error: when code runs without errors but produces incorrect results.
 Here the program runs without crashing but result is wrong.
 age = 20
print(age + 10)
If your intention was to calculate the birth year, this code is logically incorrect even though Python is perfectly happy to run it.

## The Mindset Shift

Don't ask:

"How do I write code?"

Instead ask:

"How can I break this problem into small, precise steps?"

That's the core skill of programming.
