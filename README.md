# int2bitstrproject
This project was compiled all together in terminal using the following commands
gcc -Wall -g -m32 -c tester.c
gcc -Wall -g -m32 -c int2bitstr.c
gcc -Wall -g -m32 -o xtest tester.o int2bitstr.o
The file int2bitstr contains two methods
int2bitstr is a method that stores the bit pattern of a 32 bit integer as a string of binary 1 or 0 of the same length

