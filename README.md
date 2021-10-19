# int2bitstrproject
This project was compiled all together in terminal using the following commands
gcc -Wall -g -m32 -c tester.c
gcc -Wall -g -m32 -c int2bitstr.c
gcc -Wall -g -m32 -o xtest tester.o int2bitstr.o
The file int2bitstr contains two methods, int2bitstr and get_exp_value.
int2bitstr is a function that stores the bit pattern of a 32 bit integer as a string of binary 1 or 0 of the same length
get_exp_value is a function  that calculates the exponent value of float f and returns it. the input for f is given by the user
the file tester contains a test case to use the code in order to demonstrate the results of both functions.
