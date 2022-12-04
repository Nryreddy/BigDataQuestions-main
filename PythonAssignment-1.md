
## Assignment Part-1

Q1. Why do we call Python as a general purpose and high-level programming language?

    >> Python is a general-purpose language, which means it's designed to be used in a range of applications, including data science, software and web development. High-level programming language because they are not written in machine-readable language.

Q2. Why is Python called a dynamically typed language?

    >>  Dynamically typed language because the variable types are automatically determined at run time, so it doesn't require a declaration of variables at the time of code.

Q3. List some pros and cons of Python programming language?

    >> Pros of Python
    1. Easy to Read, Learn and Write
    2. Improved Productivity
    3. Interpreted Language
    4. Dynamically Typed
    5. Free and Open-Source

    Cons of Python
    1. Slow Speed
    2. Not Memory Efficient
    3. Weak in Mobile Computing
    4. Database Access

Q4. In what all domains can we use Python?

    >> Web development,Data science,OS development,Scientific programming,Gaming,AI,ML,Building Apps.

Q5. What are variable and how can we declare them?

    >> A Python variable is a symbolic name that is a reference or pointer to an object. Once an object is assigned to a variable, you can refer to the object by that name.In Python, we don't declare variables, we simply assign them.

Q6. How can we take an input from the user in Python?

    >> The input function is used.It takes the input from the user and then evaluates the expression.

Q7. What is the default datatype of the value that has been taken as an input using input() function?

    >> String.

Q8. What is type casting?

    >> Type Casting is the method to convert the variable data type into a certain data type by users.

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?

>> Yes 
using split() method and List comprehension.

Q10. What are keywords?

    >> Python keywords are special reserved words that have specific meanings and purposes and can't be used for anything but those specific purposes.
    
Q11. Can we use keywords as a variable? Support your answer with reason.

    >> We cannot use a keyword as a variable name, function name, or any other identifier. They are used to define the syntax and structure of the Python language. All the keywords except True , False and None are in lowercase and they must be written as they are.

Q12. What is indentation? What's the use of indentaion in Python?

    >> 
    Indentation refers to the spaces at the beginning of a code line. Where in other programming languages the indentation in code is for readability only .Python indentation refers to adding white space before a statement to a particular block of code. In another word, all the statements with the same space to the right, belong to the same code block.

Q13. How can we throw some output in Python?

    >> The basic way to throw output is by print statement.

Q14. What are operators in Python?

    >> Operators are used to perform operations on variables and values.we use the + operator to add together two values:

Q15. What is difference between / and // operators?

    >> In Python programming, you can perform division in two ways. The first one is Float Division("/") and the second is Integer Division("//") or Floor Division.

Q16. Write a code that gives following as an output.

```
iNeuroniNeuroniNeuroniNeuron
```
    >>  print('iNeuroniNeuroniNeuroniNeuron')

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.

>>
n = int(input('enter a number - '))

if n%2==0:

    print('even number')

else:

    print('odd number')


Q18. What are boolean operator?

    >> The logical operators and, or and not are also referred to as boolean operators.


Q19. What will the output of the following?

```
1 or 0    
>ans>  1

0 and 0    
>ans>  0

True and False and True   
>ans> False

1 or 0 or 0   
>ans>  1
```

Q20. What are conditional statements in Python?

    >>A conditional statement as the name suggests itself, is used to handle conditions in your program. These statements guide the program while making decisions based on the conditions encountered by the program.
    Python has 3 key Conditional Statements that you should know:if statement,if-else statement,if-elif-else ladder.


Q21. What is use of 'if', 'elif' and 'else' keywords?

    >> common way to control the flow of a program.


Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
   
>>

age = int(input())

if age>=18:

    print("I can vote")

if age < 18 :

    print("I can't vote")



Q23. Write a code that displays the sum of all the even numbers from the given list.

```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
>>  

numbers = [12, 75, 150, 180, 145, 525, 50]

def sum_of_even_num(n):

    sum=0

    for i in n:

        if i%2==0:

            sum=sum+i

        else:

            continue

    print(sum)

sum_of_even_num(numbers)


Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

>> 

n = input("enter 1st numbers - ")

m = input("enter 2nd numbers - ")

j = input("enter 3rd numbers - ")

g_num = max(n,m,j)

print("The gretest number is -> ",g_num)
    

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```

>>

numbers = [12, 75, 150, 180, 145, 525, 50]

def cond_func(num):

    for n in num:

        if n%5==0:

            if n>500:

                break

            if n>150:

                continue
                
            print(n)

cond_func(numbers)