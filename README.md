# EqualityPrinter
# Challenge from Tim Buchalka's Java Programming Masterclass for Software Developers course.

Write a method printEqual with 3 pararmeters of type int. The method should not return anything (void).

If one of the parameters is less than 0, print text "Invalid Value".

If all numbers are equal print text "All numbers are equal".

If all numbers are different print text "All numbers are different".

Otherwise, print "Neither all are equal or different".

EXAMPLES OF INPUT/OUTPUT:

  * printEqual(1, 1, 1); should print text All numbers are equal
  
  * printEqual(1, 1, 2); should print text Neither all are equal or different
  
  * printEqual(-1, -1, -1) should print text "Invalid value"
  
  * printEqual(1, 2, 3); should print text All numbers are different
  
  TIP: Be extremely careful about spaces in the printed message.
  
  NOTES:
  
    * The method printEqual needs to be defined as public static.
    
    * Do not add main method to solution code.
