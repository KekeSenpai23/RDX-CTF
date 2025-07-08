## Buffer Overflow
This was a very simple Ret2win challenge (idek why I am writing a writeup for this... but why not). There was a buffer overflow at 24. So I gave it 16 random generated pattern, a elf.bss section to write to, and redirected to the address of the win function. That gave us the flag (You could also do it through ROP chain.
