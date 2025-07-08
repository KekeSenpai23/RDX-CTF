## Heap Overflow Writeup
This challenge was a heap challenge (as expected from the name). So, first of all I analyzed the binary in IDA to see the source code as it wasn't provided with the challenge. Upon Analysing the binary I found that the pointer of the allocated chunk gets xored with a global key.
<br>
<img width="850" height="211" alt="Image" src="https://github.com/user-attachments/assets/32e2d637-0770-48a0-8e61-711d492c721c" />
