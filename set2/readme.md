TODO: Reflect on what you learned this week and what is still unclear.

Notes:
- To make the string in uppercase letter, use this function:
a_string.upper(), where the part of a_string can be any variable depending on what you want to name it.
- != means not equal to.
- % means modulud or remainder.
- the order is; if, elif then else.
- variable.append() means adding something inside the ().
- variable = [] means an empty list.
- 'for i in range(10)' means that i starts from 0
- 'for j in range(10)' means that running the code faster (?)
- for variable that contain numbers, use str() function.
- The format for coordinates:
"coordinates_row.append('(i{},j{})'.format(i,j))"
- To create a wedge pattern, the j part is like this:
'for j in range(i+1)'

**Thoughts on this course**
After doing this exercises, I might need some more practice or some lectures in order for me to have deep understand in this course. So far, I can say that I'm kinda lost right now and sir, if you are reading this, is there any youtube videos or practice websites that can help me to improve?


**HW**
Practice Question - Chapter 1

1. 
* = operator
'hello' = values
-88.8 = values
- = operator
/ = operator
+ = operator
5 = values

2.
spam = variable
'spam' = string

3. 3 Data Types are: Integer, Floating-Point and String

4. It consist of values and operators and they can always evaluate(that is, reduce) down to a single value. 

5. For Assignment statements, it consist of variable name, an equal sign (called the assignment operator) and the value to be stored. While for Expression, it evaluates the values to a single value.

6. 21

7. 'spam'+'spamspam' = 'spamspamspam'
'spam' * 3 = 'spamspamspam'

8. Because can't begin with a number.

9. str(), int() and float()

10. Because 'I have eaten' and 'burritos' are strings while 99 is a value (integer). Strings and values cannot be added together. Therefore, 99 should be added with '' in order to become a string. So:
'I have eaten' + '99' + 'burritos'



Practice Question - Chapter 2

1. True and False.
The front letters 'T' and 'F' should be capitalised and the rest is in lowercase.

2. and, or and not

3. 
AND
True and True = True
True and False = False
False and True = False
False and False = False

OR
True or True = True
True or False = True
False or TRue = True
False or False = False

NOT
not True = False
not False = True

4. 
(5 > 4) and (3 == 5)
False
not (5 > 4)
False
(5 > 4) or (3 == 5)
True
not ((5 > 4) or (3 == 5))
True
(True and True) and (True == False)
False
(not False) or (not True)
True

5. 
== <- Equal to
!= <- Not Equal to
<  <- Less than
> <- Greater than
<= <- Less than or equal to
>= <- Greater than or equal to

6. 
The = operator (assignment) puts the value on the right into the variable on the left
The == operator 9equal to) asks whether two values are the same as each other.

7. 
Condition is just more a specific name in the context of flow control statements. It's always evaluate down to a Boolean value, True or False. It's used in a flow control statements, whether it's True or False.

8. The three block of codese are everything inside the if statement:

print('bacon') and print('ham').
print('eggs')
if spam > 5:
print('bacon')
else:
print('ham')
print('spam')

9. 
spam = 0

if spam == 1:
  print('Hello')
if spam == 2:
  print('Howdy')
else:
  print('Greetings!')

10.
Press ctrl-C to stop the program from being stuck in an infinite loop.

11. The purpose of break statements is to exit or "break" a for or while conditional loop. Whereas for the continue statement, it's used to skip code within a loop for certain iterations of the loop. 

12. 
For range(10), by default it starts from 0 to but then, stop  at 9.  
For range(0,10), it will starts from 0 but then stop at 9, not including the number 10 to stop at.  
For range(0,10,1), it will start from 0 to 10 by intervals of 1. 

13. 
for i in range(1,11):
  print(i)

i=1
while i <= 10:
  print(i)
  i=i+1

14. spam.bacon()



Practice Question - Chapter 3

1. Functions are like a miniprogram within a program. The purpose of functions is to group code that gets executed multiple times. Without it, we would have to copy and paste codes which is a waste of time. It's easier to read and update when it comes to functions. 

2. The code in a function executes when the function is called, not defined.

3. def statement 

4. The purpose of a function is to create since it consist of def statement. As for the function call, is a code that is used to pass control to a function.

5. There is one global scopes in a Phyton program and local scope is created whenever a function is called.

6. The local scope will be destroyed and all of the variables inside it will be forgotten.

7. The value that a function call evaluates to is called the return value of the function. And yes, the return value can be used as an expression just like any other values.

8. Its called the 'None' value.

9. The Global statement will force a variable in a function to refer to the global variable.

10. Its NoneType.

11. The purpose of an import statement is to import a module named areallyyourpetsnamederic.

12. spam.bacon()

13. Put the code in a try clause and have an except clause contain code to handle what happens when this error occurs.

14. When a code in a try clause causes an error, the program execution immediately moves to the code in the except clause. Once the execution jumps to the code in the except value, it does not return to the try clause. Instead it will just continue moving down the program as normal.

PRACTICE PROJECT:





