# Chapter 10: Error Handling And Debugging

### ORDER OF EXECUTION 
>To find the source of an error, it helps to know how scripts are processed. 
>The order in which statements are executed can be complex; some tasks 
>cannot complete until another statement or function has been run:

### Hosting 
1: PREPARE 
• The new scope is created 
• Variables, functions, and arguments are created 
• The value of the this keyword is determined


#### Understanding that these two phases happen helps 
with understanding a concept called hoisting. You 
may have seen that you can: 
• Call functions before they have been declared 
(if they were created using function declarations 

• Assign a value to a variable that has not yet been 
declared


## ERROR OBJECTS CONTINUED

1.Syntax Error 
SYNTAX IS NOT CORRECT 
This is caused by incorrect use of the rules of the 
language. It is often the result of a simple typo. 

2.ReferenceError 
VARIABLE DOES NOT EXIST 
This is caused by a variable that is not declared or is 
out of scope.

3.UR I Error 
INCORRECT USE OF URI FUNCTIONS 
If these characters are not escaped in URls, they 

4.Type Error 
VALUE IS UNEXPECTED DATA TYPE 
This is often caused by trying to use an object or 
method that does not exist.

5.RangeError 
NUMBER OUTSIDE OF RANGE 
If you call a function using numbers outside of its 
accepted range.

6. Error 
GENERIC ERROR OBJECT 
The generic Error object is the template (or 
prototype) from which all other error objects are 
created.
7.NaN 
NOT AN ERROR 
Note: If you perform a mathematical operation using 
a value that is not a number, you end up with the 
value of NaN, not a type error. 
NOT A NUMBER 


### How to deal with the errors
1.: DEBUG THE SCRIPT TO FIX ERRORS 
If you come across an error while writing a script 
(or when someone reports a bug), you will need to 
debug the code, track down the source of the error, 
and fix it.
2: HANDLE ERRORS GRACEFULLY 
You can handle errors gracefully using try, catch, 
throw, and f i na 1 ly statements. 