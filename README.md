# Oll Interpreter  

An interpreter for a custom stack-based programming language called **Oll**.  
This project includes the main interpreter script (`interpreter.py`) and example programs written with the `.oll` extension.

## Features
- Supports stack-based operations like `PUSH`, `POP`, `ADD`, `SUB`, etc.
- Includes conditional and labeled jumps: `JUMP.EQ.0`, `JUMP.GT.0`.
- Provides basic input and output functionality with `READ` and `PRINT`.
- Executes `.oll` programs efficiently by simulating a stack and program counter.

## Instructions
| Instruction      | Description                                                                |
|------------------|----------------------------------------------------------------------------|
| `PUSH <number>`  | Pushes a number onto the stack.                                            |
| `POP`            | Removes the top value from the stack.                                      |
| `ADD`            | Pops two values, adds them, and pushes the result back onto the stack.     |
| `SUB`            | Pops two values, subtracts the second from the first, and pushes the result.|
| `PRINT`          | Prints the specified string or stack value.                               |
| `READ`           | Reads a number from the user and pushes it onto the stack.                |
| `JUMP.EQ.0 <L>`  | Jumps to label `<L>` if the top of the stack is `0`.                      |
| `JUMP.GT.0 <L>`  | Jumps to label `<L>` if the top of the stack is greater than `0`.          |
| `HALT`           | Terminates the program.                                                   |

## Write Your Oll Program
Create a program using the Oll syntax and save it with a .oll extension, for example, example.oll.

## Run the Interpreter:
Execute the interpreter with your .oll program file:

`python3 interpreter.py path/to/your_program.oll`

eg: `python3 interpreter.py program1.oll`

### Note
This repository includes the following `.oll` programs:

1. **`program1.oll`**: Checks if two numbers are equal.
2. **`program2.oll`**: Checks whether a given number is odd or even.
3. **`program3.oll`**: Compares three values and prints the greatest one.  
