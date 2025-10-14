[Personal Learning Record](../../personal_learning_record/personal_learning_record.md) | [Session Notes](../sessions/README.md) 

# Session 2

## Topics covered

Introduction to computer architecture, understanding how computer systems are built from key components.

Turing Machines and the Von Neumann architecture including main CPU components. On the CPU, the main components are registers, the arithmetic logic unit, caches L1 & L2, and the memory management unit. Outside the CPU, computers use RAM and storage HDD/SSDs.

CPU Architectures - RISC, reduced instruction set computer - ARM processors like Raspberry Pi and CISC, complex instruction set computer – used in PCs.

Binary Arithmetic and Boolean Logic- binary/ hexadecimal number systems, binary addition, subtraction, multiplication, and division, boolean algebra operations using logic gates.

Adders, half-adders, flip-flops, registers, and counters and how they combine to form a simple 4-bit CPU.

## Personal Notes and research following this session

The Von Neumann architecture is the foundation for most modern computers. It separates memory, processing, and control, which helps instructions execute more organisedly.

I learnt how Turing Machines introduced programmable systems, any modern computer can simulate a Turing machine.

I explored the differences between RISC and CISC processors:
-RISC has fewer, simpler instructions, making it more efficient for low-power devices like the Raspberry Pi.
-CISC has a larger instruction set and is more powerful for desktop systems like PCs.

We practised using binary and hexadecimal conversions and how hexadecimal helps make binary easier for us to read.

Two’s complement arithmetic lets computers show negative numbers without needing extra subtraction parts. We take the positive number, flip it and add 1. For example 5 - 0101, flip all the bits - 1010 and add 1 - 1011.

Logic gates and adders and flip-flops. (need a better understanding on this - ask craig)

I installed Git on Windows and learned how to clone repositories locally, using a Personal Access Token for authentication.

## Exercises and results

Installed Git on my personal computer and confirmed it worked, generated a Personal Access Token for authentication, cloned my forked GitHub repository to my PC and merged it with the latest branch.

We looked at half adder and full adder circuits to see how carry bits work during addition and looked at a 4-bit online simulation to see how data is stored and counted. We learnt about its instruction set - IN, OUT, ADD, SUB, AND, OR, etc, and decoded our own example. 

## Summary of learning

I have a better understanding of how computers are built — from basic binary and logic operations to how a CPU processes instructions.

The Von Neumann architecture helped me see how CPU memory, storage, and I/O work together.

Learning about binary arithmetic and two’s complement gave me understanding of how computers deal with positive and negative numbers.

The Git exercises made me more confident in managing repositories and version control locally and online.

Comparing RISC and CISC architectures helped me understand why ARM processors focus on energy efficiency and Intel CPUs focus on performance.
