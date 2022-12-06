## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?
Ans. General purpose: In different apps, search engines , games, softwares, etc. Python plays a vital role in the implementation and its working.

High-level programming language: Because it is a object-oriented programming language which is easy for humans to understand.

Q2. Why is Python called a dynamically typed language?
Ans. We don't need to declare the type of variable in python which makes it dynamic!

Q3. List some pros and cons of Python programming language?
Ans. Pros: Easy to learn, Extensive libraries, Powerful and highly used language 
Cons: Not easy to test, high memory usage/consumption

Q4. In what all domains can we use Python?
Ans. Game development, Web development, ML / AI, OS development, Data science/Data analytics and data visualization, Mobile apps, etc.

Q5. What are variable and how can we declare them?
Ans. Variable is a name assigned to a memory location. Variables can be declared simply by assigning value to it.

Q6. How can we take an input from the user in Python?
Ans. Using input function i.e. input(), python takes the input from the user and then evaluates the expression. The interpreter automatically identifies whether a user input is a string, number, or a list.

Q7. What is the default datatype of the value that has been taken as an input using input() function?
Ans. String.

Q8. What is type casting?
Ans. Changing one form of variable data type to another data type. 
Ex a= 5 (int)
a=str(a)
print('Datatype is',type(a)) , Datatype is <class 'str'>

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
Ans. Yes, using split() or list method.
ex: for split()
p,q,r=input('Enter the three values').split()
print('Age of Abhishek is: ',p)
print('Age of Abhinav is: ',q)
print('Age of Abhilasha is: ',r)
----------------------------------
ex: list
x, y = [int(x) for x in input("Enter two values: ").split()]
print("First age is: ", x)
print("Second age is: ", y)

Q10. What are keywords?
Ans. Keywords are words having specific meaning and action which can be used anytime and do not need to be imported. 
Ex: True, False, if, elif, del, and, or, among others.

Q11. Can we use keywords as a variable? Support your answer with reason.
Ans. No. They're predefined words by Java so they cannot be used as a variable.

Q12. What is indentation? What's the use of indentaion in Python?
Ans. Indentation is the space at the beginning of a code line. In Python, indentation is used to indicate a block of code and will throw an error if not used properly.

Q13. How can we throw some output in Python?
Ans. By using the print function i.e print() for a given object.

Q14. What are operators in Python?
Ans. Operators are special symbols that perform operations on variables and values. Different types are:
Arithmetic operators
Assignment Operators
Comparison Operators
Logical Operators
Bitwise Operators
Special Operators

Q15. What is difference between / and // operators?
Ans. / : Gives quotient as o/p (can be a float value)  ;  // : Gives a constant value (cannot be a float value)
Ex: 
a=23
b=7
print('Value for / is: ',a/b)
print('Value for // is: ',a//b)
----------------------------------------------
o/p: Value for / is:  3.2857142857142856
Value for // is:  3

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
Ans. 
a='iNeuron'
print(a*4)

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
Ans. 
a=int(input('Enter a number!!'))
if  (a%2==0):
    print('Even!!!')
else:
    print('Odd!!!')    

Q18. What are boolean operator?
Ans. Logical operators and, or and not are referred to as boolean operators. 
And/or operator needs two operands, which may evaluate to true or false, not operator needs one operand evaluating to true or false.
Boolean and operator returns true if both operands return true. 
Boolean or operator returns true if any one operand is true.
Not operator returns true if its operand is a false expression and returns false if it is true.

Q19. What will the output of the following?
```
1 or 0

0 and 0

True and False and True

1 or 0 or 0
```
Ans. 
1 or 0 - 1

0 and 0 - 0

True and False and True - False

1 or 0 or 0 - 1

Q20. What are conditional statements in Python?
Ans. Conditional statements are handled by IF statements in Python. Different logical conditions  used in python are:
Equals: a == b
Not Equals: a != b
Less than: a < b
Less than or equal to: a <= b
Greater than: a > b
Greater than or equal to: a >= b

Q21. What is use of 'if', 'elif' and 'else' keywords?
Ans. if : Used to pass a condition
else : Used when we want to judge one statement on the basis of other. If one condition goes wrong then other has to be right.
elif : Act as a third condition and used when the other condition goes wrong or incorrect

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
Ans.
age=int(input('Enter you age!!'))
if  (age>=18):
    print('I can vote')
else:
    print("I can't")    

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
Ans. 
a = [12, 75, 150, 180, 145, 525, 50]
b =0
for num in a:
    if (num%2==0):
        b=b+num
print(b)
```
Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
Ans. 
a =int(input("Enter first number"))
b =int(input("Enter second number"))
c =int(input("Enter third number"))
if(a>b and a>c):
    print(a)
elif(c>b and c>a):
    print(c)
else:
    print(b)

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
Ans. 
a = [12, 75, 150, 180, 145, 525, 50]
for num in a:
    if(num>150):
        continue
    elif(num%5==0):
        print(num)
    elif(num>500):
        break   

Output: 
75
150
145
50