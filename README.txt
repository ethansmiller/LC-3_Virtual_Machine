This project was a virtual machine for the LC-3 from a guide written by Justin Meiners and Ryan Pendleton (found at: https://justinmeiners.github.io/lc3-vm/).

The purpose of this project was to further familiarize myself with the C-coding language as well as fundamentals of assembly language. As LC-3 is a fictional computing system based around assembly language given a much simpler instruction set and defined limits, this project proved to be useful in furthering my knowledge and experience.

This file contains the source code I wrote as I progressed through the guide given above, as well as an executable file for the VM, and two object files '2048' and 'rogue' both written by the authors of the project guide.

HOW TO RUN:

After acquiring the files provided in the GitHub repository, compile the program in any given C compiler (ex: 'gcc -o lc3_vm.exe lc3_vm.c' in command prompt using mingw).

Next, run the executable file along with one of the two object files as arguements (ex: 'lc3_vm.exe 2048.obj/rogue.obj' in command prompt).