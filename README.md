# C_Class - 001
# 
Compiler          -> Turbo C    ->  VI Editor ()
Operating System  -> Windows    ->  Linux 
Hardware          -> X86        ->  X86



Human -: Maschine
Compiler -: .c to .exe
IDE -: code written into IDE (Predefine Library) (Notpad without indication)

Native -:
Cross Compiler -:

Windos-: Visual Studio
Linux -: VI Terminal 

Basic C Language Structure

/*  Hellooworld.c */

1. Include the Header files(Pre Processor Directives)
2. Function Prototypes or Function Declaration
3. Gloabal Variables
4.Minimum 1 Function
#include<stdio.h>
   main()
   {
      local variables  
      logic  
      Call functions
  }
5. Other Functions body

#include<stdio.h>
/* Header file Consists of Declaration */
  (function declaration,
   structure declaration,
   typesdef,
    #defines(macro),
    unions
)

Functions -: 
 1. Declaration / Prototypes
 2. Defination
 3. Call
  Policy -: Before calling that function should be declared
    Declaration-: Imformation passed to compiler
   
Bug -: Logical Errors 


int my_sum(int , int ) ; // declaration


main()
{
   
  int j;
   
    j=my_sum(30,35); // function call



}
int my_sum(int a , int b)  // function body //function defination
{

    return a +b ;

}
-------------------------------------------------------------------------------------------------------

Primary Data Type -:
   char 
   integer
   float 
   double
   
 
 char -:
--------------------
  char ch=10;

  
Size -: 1 Byte

	0000 0000 = Minimum   = 0
	1111 1111 = Max =0xFF = 2^8 = 256
			
			1 
   10000 0000			
 
  0 1 2 3 4...........255

0x0000 Location -: Byte reserve = 10 Value

00000 1010 = 

  unsigned char 
  ----------------
  Size - 1 Byte 
  Store - positive number 
  Range -: 0...255
  
  
  signed char (If we not declared any type than it will take bydefault signed value)
  ----------------
  Size - 1 Byte 
  Store - positive/Negative number
  Range -: -128 0...+127
  
          -128 -127  -126 -125 ....... -3 -2 -1 0 1 2 3 4 .....+127
		  
		  signed char ch= 130 
		                 -127
						 -----
						    3 -1  = 2  for rolled out
                        mini = -128 +2 = -126
						
	How to store negative numbers in char = 2's complement Methode
	
	signed char ch= -6;
	
	0000 0110 = Absolute value of Digit
	
	1111 1001 = 1's complement
+           1 = Adding 1
====================
    1111 1010 =
	
	      8421
	128 +32 +64 +16 +8 +2 
	
	unsigned char ch = -6 ;
	
====================================================

Compilation Stages -: 
