## Python OOP Assignment
Q1. What is the purpose of Python's OOP?

    It main purpose is to implement real-world entities like inheritance, polymorphisms, encapsulation, etc. in the programming.

Q2. Where does an inheritance search look for an attribute?

    An inheritance search looks for an attribute first in the instance object, then in the class the instance was created from, then in all higher superclasses, progressing from left to right (by default).    

Q3. How do you distinguish between a class object and an instance object?

    -Object is an instance of a class. 
    -Class is a blueprint or template from which objects are created. 
    -Object is a real world entity such as pen, laptop, mobile, bed, keyboard, mouse, chair etc. 
    -Class is a group of similar objects.

Q4. What makes the first argument in a class’s method function special?

    self represents the instance of the class. By using the “self”  we can access the attributes and methods of the class in python. It binds the attributes with the given arguments.

    The reason you need to use self. is because Python does not use the @ syntax to refer to instance attributes. Python decided to do methods in a way that makes the instance to which the method belongs be passed automatically, but not received automatically: the first parameter of methods is the instance the method is called on.

Q5. What is the purpose of the init method?

    The __init__ method lets the class initialize the object's attributes and serves no other purpose.

Q6. What is the process for creating a class instance?

    To create instances of a class, you call the class using class name and pass in whatever arguments its __init__ method accepts.

Q7. What is the process for creating a class?

    In Python, a class can be created by using the keyword class, followed by the class name. The syntax to create a class is given below.
    For instance :
        Class Class_name:
            var_1
            var_2
            Objects of class ...

Q8. How would you define the superclasses of a class?

    A superclass is the class from which many subclasses can be created .

    #Parent Class
    class Course(object):
          # Constructor 
          def __init__(self, CourseName,Topic): 
              self.CourseName =CourseName
              self.Topic=Topic

    # Inherited or Sub class  
    class Author(Course): 
        #Constructor
        def __init__(self,CourseName,Topic,Authorname):
            #deriving attributes of Parent Class
            Course.CourseName=CourseName
            Course.Topic=Topic

            #adding a new attribute to the subclass
            self.Authorname=Authorname

        def printCourseDetails(self):
            print(Course.CourseName,Course.Topic,self.Authorname)

    #The three consecutive inputs will take name of the course,one of the topics from that course and the name of author who writes a post for that     topic and will print them in order.
    user_input=Author(input(),input(),input())
    user_input.printCourseDetails()

Q9. What is the relationship between classes and modules?

    Modules are collections of methods and constants. They cannot generate instances. Classes may generate instances (objects), and have per-instance state (instance variables)

Q10. How do you make instances and classes?

    To create instances of a class, We call the class using class name and pass in whatever arguments its __init__ method accepts.

Q11. Where and how should be class attributes created?

    class Circle:
    pi = 3.14159

    def __init__(self, radius):
        self.radius = radius

    def area(self):
        return self.pi * self.radius**2

    def circumference(self):
        return 2 * self.pi * self.radius

Q12. Where and how are instance attributes created?

    Instance attributes are defined in the constructor. Defined directly inside a class. Defined inside a constructor using the self parameter.

Q13. What does the term "self" in a Python class mean?

    The self parameter is a reference to the current instance of the class, and is used to access variables that belongs to the class.

Q14. How does a Python class handle operator overloading?

    The operator overloading in Python means provide extended meaning beyond their predefined operational meaning. Such as, we use the "+" operator for adding two integers as well as joining two strings or merging two lists. We can achieve this as the "+" operator is overloaded by the "int" class and "str" class.

Q15. When do you consider allowing operator overloading of your classes?

    Consider that we have two objects which are a physical representation of a class (user-defined data type) and we have to add two objects with binary '+' operator it throws an error, because compiler don't know how to add two objects. So we define a method for an operator and that process is called operator overloading.

Q16. What is the most popular form of operator overloading?

    A very popular and convenient example is the Addition (+) operator. Just think how the '+' operator operates on two numbers and the same operator operates on two strings. It performs “Addition” on numbers whereas it performs “Concatenation” on strings.

Q17. What are the two most important concepts to grasp in order to comprehend Python OOP code?

    Both inheritance and polymorphism are fundamental concepts of object oriented programming. These concepts help us to create code that can be extended and easily maintainable.

Q18. Describe three applications for exception processing.

    Unlike system exceptions, application exceptions are not used to report system-level errors. Instead, business methods use application exceptions to notify the client of application-level activity that might cause errors; for example, invalid input argument values to a business method.

Q19. What happens if you don't do something extra to treat an exception?

    Execution of program is stopped,even though the code is syntatically correct . 

Q20. What are your options for recovering from an exception in your script?

    We can provide a generic except clause by using try catch method, which handles any exception. 
    After the except clause(s), we can include an else-clause.

Q21. Describe two methods for triggering exceptions in your script.

    Try – This method catches the exceptions raised by the program. Raise – Triggers an exception manually using custom exceptions.

Q22. Identify two methods for specifying actions to be executed at termination time, regardless of  
whether or not an exception exists.

    Try,catch and finally can be used for specifying actions to be executed at termination time, regardless of  
    whether or not an exception exists.

Q23. What is the purpose of the try statement?

    To Execute normal working code,where the possibility of Exception can occur .

Q24. What are the two most popular try statement variations?


Q25. What is the purpose of the raise statement?

    Raise – Triggers an exception manually using custom exceptions.


Q26. What does the assert statement do, and what other statement is it like?

    It lets you test if a condition in your code returns True, if not, the program will raise an AssertionError

Q27. What is the purpose of the with/as argument, and what other statement is it like?

    The with statement is a replacement for commonly used try/finally error-handling statements.

Q28. What are *args, **kwargs?

    *args specifies the number of non-keyworded arguments that can be passed and the operations that can be performed on the function in Python whereas **kwargs is a variable number of keyworded arguments that can be passed to a function that can perform dictionary operations.

Q29. How can I pass optional or keyword parameters from one function to another?

    Users can either pass their values or can pretend the function to use theirs default values which are specified. In this way, the user can call the function by either passing those optional parameters or just passing the required parameters. Without using keyword arguments. By using keyword arguments

Q30. What are Lambda Functions?

    Lambda Functions are one liner Functions .

Q31. Explain Inheritance in Python with an example?

    Inheritance relationship defines the classes that inherit from other classes as derived, subclass, or sub-type classes.

Q32. Suppose class C inherits from classes A and B as class C(A,B).Classes A and B both have their own versions of method func(). If we call func() from an object of class C, which version gets invoked?

    Func() from class A and B will be invoked .    

Q33. Which methods/functions do we use to determine the type of instance and inheritance?

    Using isinstance() function, we can test whether an object/variable is an instance of the specified type or class such as int or list. In the case of inheritance, we can checks if the specified class is the parent class of an object.

Q34.Explain the use of the 'nonlocal' keyword in Python.

    The nonlocal keyword is used to work with variables inside nested functions, where the variable should not belong to the inner function. Use the keyword nonlocal to declare that the variable is not local.

Q35. What is the global keyword?

    The global keyword is used to create global variables from a no-global scope, e.g. inside a function.