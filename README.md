# Mano Basic Computer
## Project Overview
This project implements a basic computer system inspired by M. Morris Mano's "Digital Design" textbook. It simulates a basic computer architecture that focuses on a simplified model of a CPU, memory, and input/output (I/O) devices.
The computer features a simple instruction set architecture (ISA), a basic set of registers, and support for fundamental operations such as addition, subtraction, and branching. It is a learning tool for understanding computer architecture and digital logic design.
## This project was designed by a team of 4 students called (creative team ) as a part of our Microcontrollers Architecture Course.
 
 ## System Components

    1- CPU (Central Processing Unit): The brain of the computer. The CPU fetches, decodes, and executes instructions from memory.

        Registers: A small set of storage locations used for temporary data storage.

        Program Counter (PC): Points to the memory location of the next instruction to be fetched.

        Instruction Register (IR): Holds the current instruction being executed.

        Accumulator (AC): A register used for arithmetic and logic operations.

   2- Memory: The system's memory stores data and instructions. It is divided into:

        Program Memory: Stores the machine code of the program.

        Data Memory: Stores variables and results from computations.

    3-Input/Output (I/O): Provides the interface to communicate with the user or external devices.

    4-Clock: Controls the timing of operations in the system.

### Instruction Set Architecture 
*[img] (https://github.com/codsalah/Mano-Basic-Computer-Using-Verilog/blob/main/images/img%20(2).png)
** [img] Basic computer instructions [https://slideplayer.com/slide/220345/1/images/15/BASIC+COMPUTER+INSTRUCTIONS.jpg ]
The basic computer uses a simple instruction set consisting of:

    Data Transfer Instructions: Load/Store data between memory and registers.

    Arithmetic Instructions: Add, subtract, etc.

    Control Instructions: Branch or jump to other instructions in memory.

    Logic Instructions: Perform logical operations such as AND, OR, etc.

#### Memory Layout

    Memory Size: 4096 words (Each word is 16 bits).

    Addressing Mode: Direct addressing.

    Program Load Location: The program is loaded starting at memory address 0.
  ## Example Instructions 
    1- INC (7020H) : Increament AC
    2- CMA (7200H ) : complement AC
    3- CLA (7800H) : Clear AC
    4-LDA (Load Accumulator): Loads the content of a memory address into the accumulator.
