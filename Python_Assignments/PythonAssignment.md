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
        
Q26. What is a string? How can we declare string in Python?

    Strings are immutable i.e once they are created they cannot be modified.
They are denoted by double quote .

    Syntax:
        String_var = "This is a String"

Q27. How can we access the string using its index?
We can access string using square brackets .

Q28. Write a code to get the desired output of the following
```
string = "Big Data iNeuron"
desired_output = "iNeuron"
```
    string[9:]

Q29. Write a code to get the desired output of the following
```
string = "Big Data iNeuron"
desired_output = "norueNi"
```
    string[:8:-1]

Q30. Resverse the string given in the above question.
    string[ : :-1]

Q31. How can you delete entire string at once?
    del String_name

Q32. What is escape sequence?
    new_line(\n) , tab(\t) etc are some Escape Sequence .

Q33. How can you print the below string?
```
'iNeuron's Big Data Course'
```
    String_var = 'iNeuron's Big Data Course'
    print(String_var)

Q34. What is a list in Python?
    
    They are used to store collections of data .They are represented by square brackets

Q35. How can you create a list in Python?

    ls = [1,2,'string_def',4]

Q36. How can we access the elements in a list?

    We can access them via indexing .
    ls[2]

Q37. Write a code to access the word "iNeuron" from the given list.
```
lst = [1,2,3,"Hi",[45,54, "iNeuron"], "Big Data"]
``` 
    lst[4][2]

Q38. Take a list as an input from the user and find the length of the list.

    # try block to handle the exception
    print("Enter stop to STOP the list element")
    try:
        my_list = []
    
    while True:
        my_list.append(int(input("Enter numbers to insert values:")))

    # if the input is not-integer, just print the list
    except:
        print(len(my_list))

Q39. Add the word "Big" in the 3rd index of the given list.
```
lst = ["Welcome", "to", "Data", "course"]
```
    lst.insert(3,"Big")

Q40. What is a tuple? How is it different from list?
    
    Tuples are used to store multiple items in a single variable.
    Tuple is one of 4 built-in data types in Python used to store collections of data, the other 3 are List, Set, and Dictionary, all with different qualities and usage.
    They are immutable  .

Q41. How can you create a tuple in Python?

    tuple_def = (1,2,3,4,5)

Q42. Create a tuple and try to add your name in the tuple. Are you able to do it? Support your answer with reason.

    Since tuple is immutable. we wont be able to add our name .

Q43. Can two tuple be appended. If yes, write a code for it. If not, why?

    Two tuples cannot be appended but there are work arounds ..

    test_tup1 = (1, 3, 5)
    test_tup2 = (4, 6)

    print("The original tuple 1 : " + str(test_tup1))
    print("The original tuple 2 : " + str(test_tup2))
    res = test_tup1 + test_tup2
    print("The tuple after concatenation is : " + str(res))

Q45. What are sets in Python?

    A Set is an unordered collection data type that is iterable, mutable, and has no duplicate elements. 


Q46. How can you create a set?

    var = {"this","is","Set"}

Q47. Create a set and add "iNeuron" in your set.

    var.add("iNeuron")

Q48. Try to add multiple values using add() function.

    we can add only 1 argument at a time .

Q49. How is update() different from add()?

    add() is intended for a single element , while . update() is for the introduction of other sets

Q50. What is clear() in sets?

    It is use to remove all variables from sets .

Q51. What is frozen set?

    Python frozenset() Method creates an immutable Set object from an iterable. It is a built-in Python function. As it is a set object therefore we cannot have duplicate values in the frozenset.

Q52. How is frozen set different from set?

     Python has two built-in types for sets: set and frozenset. A set is a mutable object while frozenset provides an immutable implementation.

Q53. What is union() in sets? Explain via code.

    Union of two given sets is the set which contains all the elements of both the sets.    

Q54. What is intersection() in sets? Explain via code.

    Python set intersection() method returns a new set with an element that is common to all set defined.
    for instance :
        s1 = {1, 2, 3,4,5,6,7,8,9}
        s2 = {2, 3,7}
        print(s1.intersection(s2))
    
    o/p:- 2, 3,7

Q55. What is dictionary ibn Python?

    Dictionaries are used to store data values in key:value pairs. A dictionary is a collection which is ordered*, changeable and do not allow duplicates.

Q56. How is dictionary different from all other data structures.

    Dictionary contains keys and values ,thus we can access elements via keys .

Q57. How can we delare a dictionary in Python?

    By curly brackets we can delare a dictionary in Python .

Q58. What will the output of the following?
```
var = {}
print(type(var))
```
    Dictionary

Q59. How can we add an element in a dictionary?

    using .add() function we can add elements in a dictionary .

Q60. Create a dictionary and access all the values in that dictionary.

    Dict = {1: 'Geeks', 2: 'For', 3: 'Geeks'}
    print(Dict)

Q61. Create a nested dictionary and access all the element in the inner dictionary.

    sb = {1: {'name': 'John', 'age': '27', 'sex': 'Male'},
          2: {'name': 'Marie', 'age': '22', 'sex': 'Female'}}

    print(sb)

Q62. What is the use of get() function?

    The get() method returns the value of the item with the specified key.    

Q63. What is the use of items() function?

    The items() method returns a view object. The view object contains the key-value pairs of the dictionary, as tuples in a list.

Q64. What is the use of pop() function?

    The pop() method removes the last element from an array and returns that value to the caller.

Q65. What is the use of popitems() function?

    The popitem() method removes the item that was last inserted into the dictionary.

Q66. What is the use of keys() function?

    The keys() method returns a keys view object.

Q67. What is the use of values() function?

    The values() method returns a values object.

Q68. What are loops in Python?

    Looping means repeating something over and over until a particular condition is satisfied.

Q69. How many type of loop are there in Python?

    There are two type of loop they are for loop and while loop .

Q70. What is the difference between for and while loops?

    The for and while loops are both conditional statements. A for loop is a single-line command that will be executed repeatedly. While loops can be single-lined or contain multiple commands for a single condition.     

Q71. What is the use of continue statement?

    The continue statement passes control to the next iteration .

Q72. What is the use of break statement?

    The purpose the break statement is to break out of a loop early.

Q73. What is the use of pass statement?

    The pass statement is used as a placeholder for future code    

Q74. What is the use of range() function?

    The range() function returns a sequence of numbers, starting from 0 by default, and increments by 1 .

Q75. How can you loop over a dictionary?

    Yes ,via for loop we can loop over a dictionary .

### Coding problems
Q76. Write a Python program to find the factorial of a given number.

    num = 10
    factorial = 1

    if num < 0:
        print("Sorry, factorial does not exist for negative numbers")
    elif num == 0:
        print("The factorial of 0 is 1")
    else:
        for i in range(1,num + 1):
            factorial = factorial*i
    print("The factorial of",num,"is",factorial)

Q77. Write a Python program to calculate the simple interest. Formula to calculate simple interest is SI = (P*R*T)/100

    print("Enter the Principle Amount: ")
    p = int(input())
    print("Enter Rate of Interest (%): ")
    r = float(input())
    print("Enter Time Period: ")
    t = float(input())
    si = (p*r*t)/100
    print("\nSimple Interest Amount: ")
    print(si)

Q78. Write a Python program to calculate the compound interest. Formula of compound interest is A = P(1+ R/100)^t.

    # Python program to find compound interest 

    p = float(input("Enter the principle amount : "))
    r = float(input("Enter the rate of interest : "))
    t = float(input("Enter the time in the years: "))   

    # calculating compound interest
    ci =  p * (pow((1 + r / 100), t))   

    # printing the values
    print("Principle amount  : ", p)
    print("Interest rate     : ", r)
    print("Time in years     : ", t)
    print("compound Interest : ", ci)

Q79. Write a Python program to check if a number is prime or not.

    # Program to check if a number is prime or not

    num = 29

    # To take input from the user
    #num = int(input("Enter a number: "))

    # define a flag variable
    flag = False

    if num == 1:
        print(num, "is not a prime number")
    elif num > 1:
        # check for factors
        for i in range(2, num):
            if (num % i) == 0:
                # if factor is found, set flag to True
                flag = True
                # break out of loop
                break

        # check if flag is True
        if flag:
            print(num, "is not a prime number")
        else:
            print(num, "is a prime number")


Q80. Write a Python program to check Armstrong Number.

    # take input from the user
    num = int(input("Enter a number: "))

    # initialize sum
    sum = 0

    # find the sum of the cube of each digit
    temp = num
    while temp > 0:
       digit = temp % 10
       sum += digit ** 3
       temp //= 10

    # display the result
    if num == sum:
       print(num,"is an Armstrong number")
    else:
       print(num,"is not an Armstrong number")


Q81. Write a Python program to find the n-th Fibonacci Number.

    def Fibonacci(n):
    if n<= 0:
        print("Incorrect input")
    # First Fibonacci number is 0
    elif n == 1:
        return 0
    # Second Fibonacci number is 1
    elif n == 2:
        return 1
    else:
        return Fibonacci(n-1)+Fibonacci(n-2)
 
    # Driver Program

    print(Fibonacci(10))
 

Q82. Write a Python program to interchange the first and last element in a list.

    def swapList(newList):
        size = len(newList)
        temp = newList[0]
        newList[0] = newList[size - 1]
        newList[size - 1] = temp

    return newList
    newList = [12, 35, 9, 56, 24]
    print(swapList(newList))

Q83. Write a Python program to swap two elements in a list.

    def swapPositions(list, pos1, pos2):
        list[pos1], list[pos2] = list[pos2], list[pos1]
    return list

    List = [23, 65, 19, 90]
    pos1, pos2  = 1, 3
    print(swapPositions(List, pos1-1, pos2-1))

Q84. Write a Python program to find N largest element from a list.

    def Nmaxelements(list1, N):
        final_list = []
    
        for i in range(0, N):
            max1 = 0

            for j in range(len(list1)):    
                if list1[j] > max1:
                    max1 = list1[j];

            list1.remove(max1);
            final_list.append(max1)
        print(final_list)
        list1 = [2, 6, 41, 85, 0, 3, 7, 6, 10]
        N = 2
    Nmaxelements(list1, N)

Q85. Write a Python program to find cumulative sum of a list.

    def Cumulative(lists):
        cu_list = []
        length = len(lists)
        cu_list = [sum(lists[0:x:1]) for x in range(0, length+1)]
    return cu_list[1:]
    
    lists = [10, 20, 30, 40, 50]
    print (Cumulative(lists))

Q86. Write a Python program to check if a string is palindrome or not.

    string=raw_input("Enter string:")
    if(string==string[::-1]):
          print("The string is a palindrome")
    else:
          print("The string isn't a palindrome")

Q87. Write a Python program to remove i'th element from a string.

    myStr =  input('Enter the string : ')
    i = int(input('Enter the index of character to be removed : '))
    resStr = ""
    for index in range(len(myStr)):
    	if index != i:
    		resStr = resStr + myStr[index]

    print ("Entered string : " + myStr)
    print ("String formed by removing i'th character : " + resStr)

Q88. Write a Python program to check if a substring is present in a given string.

    string=raw_input("Enter string:")
    sub_str=raw_input("Enter word:")
    if(string.find(sub_str)==-1):
          print("Substring not found in string!")
    else:
          print("Substring in string!")

Q89. Write a Python program to find words which are greater than given length k.

    def word_k(k, s):    
        # split the string where space comes
        word = s.split(" ")
        # iterate the loop for every word
        for x in word:
            # if length of current word
            if len(x)>k:
              # greater than k then
              print(x)
    k = 3
    s ="Python is good"

    word_k(k, s)

Q90. Write a Python program to extract unquire dictionary values.

    test_dict = {'gfg': [5, 6, 7, 8],
             'is': [10, 11, 7, 5],
             'best': [6, 12, 10, 8],
             'for': [1, 2, 5]}
    
    # printing original dictionary
    print("The original dictionary is : " + str(test_dict))
    
    # Extract Unique values dictionary values
    # Using set comprehension + values() + sorted()
    res = list(sorted({ele for val in test_dict.values() for ele in val}))
    
    # printing result
    print("The unique values list is : " + str(res))

Q91. Write a Python program to merge two dictionary.

    dict_1 = {1: 'a', 2: 'b'}
    dict_2 = {2: 'c', 4: 'd'}

    print(dict_1 | dict_2)

Q92. Write a Python program to convert a list of tuples into dictionary.
```
Input : [('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]
Output : {'Sachin': 10, 'MSD': 7, 'Kohli': 18, 'Rohit': 45}
```
    dict(Input)

Q93. Write a Python program to create a list of tuples from given list having number and its cube in each tuple.
```
Input: list = [9, 5, 6]
Output: [(9, 729), (5, 125), (6, 216)]
```
    list_ls = [9, 5, 6]

    res = [(val, pow(val, 3)) for val in list_ls]
    print(res)

Q94. Write a Python program to get all combinations of 2 tuples.
```
Input : test_tuple1 = (7, 2), test_tuple2 = (7, 8)
Output : [(7, 7), (7, 8), (2, 7), (2, 8), (7, 7), (7, 2), (8, 7), (8, 2)]
```

    from itertools import chain, product
  
    # initializing tuples
    test_tuple1 = (7, 2)
    test_tuple2 = (7, 8)
    # printing original tuples
    print("The original tuple 1 : " + str(test_tuple1))
    print("The original tuple 2 : " + str(test_tuple2))
    # All pair combinations of 2 tuples
    # Using chain() + product()
    res = list(chain(product(test_tuple1, test_tuple2), product(test_tuple2, test_tuple1)))
    # printing result 
    print("The filtered tuple : " + str(res))

Q95. Write a Python program to sort a list of tuples by second item.
```
Input : [('for', 24), ('Geeks', 8), ('Geeks', 30)] 
Output : [('Geeks', 8), ('for', 24), ('Geeks', 30)]
```

    def Sort_Tuple(tup):
 
    # reverse = None (Sorts in Ascending order)
    # key is set to sort using second element of
    # sublist lambda has been used
    tup.sort(key = lambda x: x[1])
    return tup
 
    # Driver Code
    tup = [('for', 24), ('Geeks', 8), ('Geeks', 30)] 
    
    # printing the sorted list of tuples
    print(Sort_Tuple(tup))


Q96. Write a python program to print below pattern.
```
* 
* * 
* * * 
* * * * 
* * * * * 
```

    rows = int(input("Enter number of rows: "))

    for i in range(rows):
        for j in range(i+1):
            print("* ", end="")
        print("\n")


Q97. Write a python program to print below pattern.
```
    *
   **
  ***
 ****
*****
```

    def patterns2(n):

        # number of spaces
        k = 2*n - 2
    
        # outer loop to handle number of rows
        for i in range(0, n):

            # inner loop to handle number spaces
            # values changing acc. to requirement
            for j in range(0, k):
                print(end=" ")

            # decrementing k after each loop
            k = k - 2

            # inner loop to handle number of columns
            # values changing acc. to outer loop
            for j in range(0, i+1):

                # printing stars
                print("* ", end="")

            # ending line after each row
            print("\r")
    
    # Driver Code
    n = 5
    patterns2(n)


Q98. Write a python program to print below pattern.
```
    * 
   * * 
  * * * 
 * * * * 
* * * * * 
```

    def triangle(n):

        # number of spaces
        k = n - 1
    
        # outer loop to handle number of rows
        for i in range(0, n):

            # inner loop to handle number spaces
            # values changing acc. to requirement
            for j in range(0, k):
                print(end=" ")

            # decrementing k after each loop
            k = k - 1

            # inner loop to handle number of columns
            # values changing acc. to outer loop
            for j in range(0, i+1):

                # printing stars
                print("* ", end="")

            # ending line after each row
            print("\r")
    
    # Driver Code
    n = 5
    triangle(n)

Q99. Write a python program to print below pattern.
```
1 
1 2 
1 2 3 
1 2 3 4 
1 2 3 4 5
```

    rows = int(input("Enter number of rows: "))

    for i in range(rows):
        for j in range(i+1):
            print(j+1, end=" ")
        print("\n")


Q100. Write a python program to print below pattern.
```
A 
B B 
C C C 
D D D D 
E E E E E 
```
    def alphapat(n):

        # initializing value corresponding to 'A'
        # ASCII value
        num = 65
    
        # outer loop to handle number of rows
        # 5 in this case
        for i in range(0, n):

            # inner loop to handle number of columns
            # values changing acc. to outer loop
            for j in range(0, i+1):

                # explicitly converting to char
                ch = chr(num)

                # printing char value
                print(ch, end=" ")

            # incrementing number
            num = num + 1

            # ending line after each row
            print("\r")
    
    # Driver Code
    n = 5
    alphapat(n)