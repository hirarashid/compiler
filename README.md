# compiler

 an interpreter in python that enable to detect syntax errors; 
 
report uninitialized variables and perform the assignments it there is no error 
and print out the values of all the variables after all the assignments are done. 

Program:

   Assignment*
   
Assignment:
     Identifier= Exp;
     
Exp:

Exp + Term | Exp - Term | Term
   
Term:

     Term * Fact | Fact
     
Fact:

    (Exp) | -Fact | + Fact | Literal | Identifier
    
Identifier:

   Letter [Letter | Digit]*
   
Letter:

     a| ...|z|A|...|z|_
     
Literal:

    0 | NonZeroDigit Digit*
    
NonZeroDigit:

    1|...|9
    
Digit:

  0|1|...|9
  
