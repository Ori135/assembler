# assembler
Contains an assembler written in the C language, created in a Linux environment.
The assembler receives the name of a file or a path to a source .as assembly text file. The program will translate the assembly code to machine code, which for simplicity, was replaced with a Base 32 Language instead of Binary. In this way, each Base 32 character represents 5 Binary characters. The program will create all necessary files for the Loading & Linking section but will not execute them.
If the assembler file has syntax or program errors (for example, too many illegal label names or an attempt to exceed the computer memory), the assembler will report all errors, their locations, and explain why the errors occurred in a similar fashion to a compiler, such as GCC.
