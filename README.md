# 32-bit Memory Access Assumption in 64-bit Assembly

This repository demonstrates a subtle bug that can occur in assembly code when making assumptions about the size of registers and memory addresses.  The bug arises from using 32-bit addressing logic in a 64-bit environment.

The file `bug.asm` contains the problematic code. The solution, which uses appropriate 64-bit addressing, is provided in `bugSolution.asm`.