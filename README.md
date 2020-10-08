# charprinter
charprinter is simple program in assembly , its used to get char from user and print it in the screen 
Usage:


    Type the above code using a text editor and save it as simpleproj.asm

    Make sure that you are in the same directory as where you saved simpleproj.asm

    To assemble the program, type nasm -f elf simpleproj.asm

    If there is any error, you will be prompted about that at this stage. Otherwise, an object file of your program named simpleproj.o will be created.

    To link the object file and create an executable file named hello, type ld -m elf_i386 -s -o simpleproj simpleproj.o

    Execute the program by typing ./simpleproj
