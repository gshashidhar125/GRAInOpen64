# GRAInOpen64
Chaitin Coloring for Global Register Allocation(GRA) Phase in Open 64 Compiler

Attached is the "gra_mon" folder of the open64 compiler to be copied at appropriate location to have the project files compiled along with the actual compiler.

opencc -O2 -c -keep -show  -Wb,-ttGRA:0xfffff 2.c

it will give the dump in "GRA_Dump.txt" and 2.t is the tracefile.
