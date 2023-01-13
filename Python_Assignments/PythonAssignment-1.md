## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language? 

    -- general purpose:
        --> We call python As General programing Language as We can create different programs from python as it is not subjected for a specific domain .
    -- high-level programming language :
        -->  Python is high-level programming language as it is easy to understand and easy to interpret .

Q2. Why is Python called a dynamically typed language?

    Python called a dynamically typed language because the type of the variable is determined only during runtime.It doesn’t know about the type of the variable until the code is run. So declaration is of no use.

Q3. List some pros and cons of Python programming language?

    --> pro:
    - Easy to understand .
    - Easy to use .
    - Fast and optimized .
    --> cons:
    - Weak in Mobile Computing .
    - Speed limitations 

Q4. In what all domains can we use Python?

        - Python Can be used in any domain for instance in Medical Industry we can use for prediction . for finance we can use for EDA  etc.
Q5. What are variable and how can we declare them?

    - Variable points to and object memory i.e its a pointer to object.
    --> Syntax :
        var_name = Int/String/char/etc...

Q6. How can we take an input from the user in Python?
    
    - Syntax :
        input(prompt)
    -Eg :
        input('Enter the input')

Q7. What is the default datatype of the value that has been taken as an input using input() function?
    -String

Q8. What is type casting?

    - Converting a variable from One datatype to another . 

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
    
    -Yes . Using Loops or via .split method

Q10. What are keywords?

    -special reserved words that cant be use for any thing other than that work . 

Q11. Can we use keywords as a variable? Support your answer with reason.

    - We can by in future it can give us Errors .thus it is not recommended .

Q12. What is indentation? What's the use of indentaion in Python?

    - indentation are Spaces that are defined after calling some loops,function,class etc. 

Q13. How can we throw some output in Python?

Q14. What are operators in Python?

     -And,or,not 

Q15. What is difference between / and // operators?

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```

    Strings = 'iNeuron'
    print(Strings*4)

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.

    num = int(input('Enter num'))
    print(num)
    if num %2 == 0:
        print("{} is even number".format(num))
    else:
        print("{} is Odd number".format(num))

Q18. What are boolean operator?
    
    AND,or,not are boolean operators .

Q19. What will the output of the following?
```
1 or 0 
Answer -> 1

0 and 0 
Answer -> 0

True and False and True
Answer -> False

1 or 0 or 0
Answer -> 1
```

Q20. What are conditional statements in Python?
    
    If else , elif,for loop switch case are conditional statement .

Q21. What is use of 'if', 'elif' and 'else' keywords?
    
    If condition is ture this block will run ..other wise elif block will run and if non of the condition is met then else block will run. 

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".

    age = int(input('Enter age'))
    print(num)
    if age >= 18:
        print("I can vote")
    else:
        print("I can't vote")

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
    ls = []

    for num in numbers:
        if num % 2 == 0:
            ls.append(num)
    print(sum(ls))

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

    num_1 = int(input('Enter first number'))
    num_2 = int(input('Enter Second number'))
    num_3 = int(input('Enter Third number'))

    if num_1 > num_2 and num_1 > num_3 :
        print("{} number is greater".format(num_1))
    elif num_2 > num_1 and num_2 > num_3 :
        print("{} number is greater".format(num_2))
    else:
        print("{} number is greater".format(num_3))


Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
for num in numbers:
    if num > 150 and num <=500 :
        if num%5==0:
            print(num)
            continue
        break```
