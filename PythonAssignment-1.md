## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?

Q2. Why is Python called a dynamically typed language?

Q3. List some pros and cons of Python programming language?

Q4. In what all domains can we use Python?

Q5. What are variable and how can we declare them?

Q6. How can we take an input from the user in Python?

Q7. What is the default datatype of the value that has been taken as an input using input() function?

Q8. What is type casting?

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?

Q10. What are keywords?

Q11. Can we use keywords as a variable? Support your answer with reason.

Q12. What is indentation? What's the use of indentaion in Python?

Q13. How can we throw some output in Python?

Q14. What are operators in Python?

Q15. What is difference between / and // operators?

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.

Q18. What are boolean operator?

Q19. What will the output of the following?
```
1 or 0

0 and 0

True and False and True

1 or 0 or 0
```

Q20. What are conditional statements in Python?

Q21. What is use of 'if', 'elif' and 'else' keywords?

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```


Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
========================================================================

Answers

Q1. Why do we call Python as a general purpose and high-level programming language?

Ans. Python can be used in many in various domain like web applications, data science, machine learning, AI mobile app, testing automation,etc its very easy to learn and implement that is why it is refered as a general purpose and high level programming language


Q2. Why is Python called a dynamically typed language?

Ans. When the code is run in Python the data type of the variable is not known, it store the value of some memory location and then binds that variable name to that memory container and makes the content of the container accessible through that variable name so the data type does not matter as it will get to know the type of the value at runtime that is why the python is called a dynamically typed language.


Q3. List some pros and cons of Python programming language?

Ans.Pros 
    1. Easy to learn
    2. Easy for development beacuse of simple sysntax
    3. Can be used in any OS mac os windows and linux and the codes can be team up with other languages.
    4. It can be used for many purpose like data science, data engineering, devops etc which makes it widely used language 

    Cons
    1. Slower then C++ and java 
    2. No Multithreading beacuse of GIL(Global Interpreter Lock)
    3. It uses high resouces and high memory consumption
    4. No suitable for smartphones 
  
Q4. Q4. In what all domains can we use Python?

Ans. Web development, Machine learning, Data Science, Data Engineering, network and internet development.


Q5. What are variable and how can we declare them?

Ans. Variable are something which store value, Python is not statically typed, so we do not have to declare variable before using them or declare their type eg:-

Name = "Junaid" 

Age = 23 

salary = 55245

print(Name)

print(Age)

print(salary)

Q6. How can we take an input from the user in Python?

Ans. Using input() we can take input (By default it will take input as string) eg:-

Name = input("Type the name ") 

Age = int(input("Type the age "))

print(Name)

print(Age)

Q7. What is the default datatype of the value that has been taken as an input using input() function?

Ans. By default it will take string as input

Q8. What is type casting?

Ans. Type casting is a way to force any datatype in a variable eg:-

Age = int(input("Type the age "))

print(Age)

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?

Ans. Yes we can take more then one input using the single input() funtion by using Split() eg:-

x, y = input("Enter two values: ").split()

print(x)

print(y)

Q10. What are keywords?

Ans. Keywords in Python are reserved words that can not be used as a variable name, function name, or any other identifier

Q11. Can we use keywords as a variable? Support your answer with reason.

Ans. No we cannot use keywords as a varibale beacuse they are case sensitive in python

Q12. What is indentation? What's the use of indentaion in Python?

Ans. Indentation is putting spaces before a statement to a particular block of code, we need to use indentation in python because it makes the code look clean and easy to understand and without proper indentation we might get IndentationError and the code will not get compiled. Eg:-

name = input("Type the name ")
 
if name == 'junaid':

print('the name is junaid')

else:

print('type the name again')

print('All set !')

Q13. How can we throw some output in Python?

Ans. We can throw output in python by using print()

Q14. What are operators in Python?

Ans. Operators are used to perform operations on variables and values. Eg:-

print(10 + 5)

print(10 - 5)

print(10 // 5)

Q15. What is difference between / and // operators?

Ans. / is regular division it return float and // is floor division it return int eg:-

print(10 // 5) #2

print(10 / 5) #2.0

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
Ans. 
for num in range (3):

print("ineoron")

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.

Ans. 

a = int(input("Type the number "))

if (a % 2 == 0):

print("The number is even")

else:

print("The number is odd")

Q18. What are boolean operator?

Ans. Boolean operator is a operator which can hold only two values either TURE or FALSE

Q19. What will the output of the following?
```
1 or 0

0 and 0

True and False and True

1 or 0 or 0
```

Ans. 

1

0

False

1

Q20. What are conditional statements in Python?

Ans. Conditional statements in Python is a statement that accommodates a condition inside itself, A conditional statement always generates a boolean output that is either true or false. eg:-

a = int(input("Type the number "))

if (a % 2 == 0):

print("The number is even")

else:

print("The number is odd")

Q21. What is use of 'if', 'elif' and 'else' keywords?

Ans. if elif and else keywords are conditional statements that accompdates a condition inside itself, for nested if else we can use elif
eg:-

if (a % 2 == 0):

print("The number is even")

else:

print("The number is odd")

marks = 54

if marks>=90:

print("Grade A+")

elif marks>=80 and marks<90:

print("Grade A")

elif marks>=70 and marks<80:

print("Grade B+")

elif marks>=60 and marks<70:

print("Grade B")

else:

print("Grade C")

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".

Ans. 
Age = int(input("Type the age = "))

if (Age >= 18):

print('I can Vote')

else:

print("i can't Vote")

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
Ans. 

numbers = [12, 75, 150, 180, 145, 525, 50]

a = 0

for i in numbers:

if i % 2 == 0:

a += i

print(a)

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

Ans. 

a = int(input("type the first number = "))

b = int(input("type the second number = "))

c = int(input("type the third number = "))

d = 0

if a > b and a > b:

d = a

if b > a and b > c:

d = b

if c > a and c > b:

d = c

print("The greatest number is = ", d)

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```

Ans. 
numbers = [12, 75, 150, 180, 145, 525, 50]

for number in numbers:

if number%5 == 0:

if number > 150:

continue

if number > 500:

break

print(number)
