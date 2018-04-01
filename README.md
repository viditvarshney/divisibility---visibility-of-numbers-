# divisibility---visibility-of-numbers-
#---------------------------------------------------------------------------------------------------------------------------------------

MADE BY VIDIT VARSHNEY 
 PASSION TO PROGRAM
 
 # QUES:-  A program to find the numbers which are divisible by 3 and 7 but are not divisible by 5 and one more thing the output must be separated by comma (" ," )
#----------------------------------------------------------------------------------------------------------------------------------------
# HINTS:-
 Consider use range(#begin, #end) method
 
#-----------------------------------------------------------------------------------------------------------------------------------------


# LOGIC

now look at the question what it says :-------
a number which is divisible by 3 , 7 but not by 5 
so it basically tells us to check the number by using conditions 
and we know that for this we use if loop 

#-----------------------------------------------------------------------------------------------------------------------------------------
# DESCRIPTION 
     WHAT WE WANT FROM THE QUESTION :------------
# i am writting this program by using list 
after that i will update the list with the numbers 
but wait questions doesn't end . question wants output only separated by "commas" 
BUT BY THE ABOVE METHOD WE FIND OUTPUT IN THIS MANNER LIKE [ '2002', '2004'......]     note:- the values like 2002,2004 are taken                                                                                                                                     randomly 
BUT WE WANT IN THIS FORM 2002,2004,2006,........
SO FOR THIS WE HAVE TO USE A LITLE CHANGE WHILE UPDATING A LIST WE MAKE ALL NUMBERS AS STRING FORMAT , THEN WHILE PRINTING THE LIST WEWE USE .join() 


#----------------------------------------------------------------------------------------------------------------------------------------

# .join()
   [ The join() method provides a flexible way to concatenate string. It concatenates each element of an iterable (such as list, string and tuple) to the string and returns the concatenated string.]
   
#----------------------------------------------------------------------------------------------

 SO IN THIS WAY OF APPROACH WE GET THE DESIRED OUTPUT 
 
 #---------------------------------------------------------------------------------------------
 
 # IF REALLY HELPS YOU CLICK THAT STAR BUTTON ON THE ABOVE RIGHT SIDE 
