# NASM-IA-32
Some assembly programmes for IA-32

Reference

1. https://asmtutor.com
2. https://cs.lmu.edu/~ray/notes/nasmtutorial/
3. https://www.tutorialspoint.com/assembly_programming/assembly_tutorial.pdf
4. https://courses.ics.hawaii.edu/ReviewICS312/morea/FirstProgram/ics312_nasm_first_program.pdf

# How to run ?

//creating the output file
1. nasm -f elf file.asm

//linking the file
2. ld -m elf-i386 file.out -o file

//executing
3. ./file                      
