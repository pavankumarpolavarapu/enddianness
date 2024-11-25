# Demo of Little & Big Endianness (https://www.youtube.com/watch?v=T8E_JRqN0fY)

- Compile the program `gcc -m32 t32.c`
- Run radare debugger `r2 -d a.out`, Analyze all program by `aa` and print disassembly function of main `pdf @ main`
- Breakpoint at memory location by `db <address>` and debug contine `dc`

