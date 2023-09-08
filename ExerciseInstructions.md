## Activity - if-else

#### INEG 2214 Computing Methods for INEG I | Fall 2023 | Submit via Push to Github main branch.

The purpose of this activity is to reinforce the concept of `if-else` statements.

Primary U.S. interstate highways are numbered 1-99. Odd numbers (like the 5 or 95) go north/south, and evens (like the 10 or 90) go east/west. Auxiliary highways are numbered 100-999, and service the primary highway indicated by the rightmost two digits. Thus, I-405 services I-5, and I-290 services I-90.

1. Within the `main` method of the class `IfElseExercise` add code to request a highway number. 

2. Check that the number given is (i) an integer and (ii) between 1 and 999. 

3. If either of the conditions in 2. are not true, display a message to the user stating why the input is valid and terminate the program. 

4. If the both conditions in 2 are true, determine whether the highway number is associated with a primary or auxiliary highway. 

5. If auxiliary, indicate what primary highway it serves. Also indicate if the (primary) highway runs north/south or east/west. 

6. Display your findings to the screen as shown below.

Ex: If the input is:
90
the output is:
I-90 is primary, going east/west.

Ex: If the input is:
290
the output is:
I-290 is auxiliary, serving I-90, going east/west.

Ex: If the input is:
0
or any number not between 1 and 999, the output is:
0 is not a valid interstate highway number.

Ex: If the input is:
1.5
the output is:
Highway number must be an integer.