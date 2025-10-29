[Walkthrough of code](http://3zanders.co.uk/2017/10/13/writing-a-bootloader/)

[Helpful Pdf](http://3zanders.co.uk/2017/10/13/writing-a-bootloader/writingabootloader.pdf) 

What i have learned.

use nasm to compile assembly code into binary.
use hexdump to read the binary file.
using qemu to show the output of the bootloader in a virtal BIOs enviroment.
16-bits vs 32-bits.
assembly operations and registers. jmp, mov, or, add, jz(jump if zero)
What gdt is "Global Descriptor Table".
creating labels. .loop: halt:
protected mode, real mode. they are allowed different amount of memory.
Writing to the VGA text buffer instead of the BIOS.

