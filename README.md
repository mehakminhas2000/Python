# Python Tasks 1 & 2

#Task 1 : Performed Basic Mathematical Operations

Problem Statement: to write a Python program that does the following:
1.  Takes two numbers as input from the user.
2.  Performs the basic mathematical operations on these two numbers:
o	Addition
o	Subtraction
o	Multiplication
o	Division
3.  Displays the results of each operation on the screen.
   
   code - num1= int(input("Enter the first number: "))     #took first num from user converting it to int datatype
          num2= int(input("Enter the second number: "))     #took second num from user converting it to int datatype
                      #then peroformed all the arithmetic operations
          add = num1 + num2 
          sub = num1 - num2
          mul = num1 * num2
          div = num1 /num2
                  #used f formatting which can be used to print different datatypes
          print(f"Addition: {add}\nSubtraction: {sub}\nMultiplication: {mul} \nDivision: {div}")
    Output - Enter the first number: 5
             Enter the second number: 10
             Addition: 15
             Subtraction: -5
             Multiplication: 50 
             Division: 0.5

Task 2: Create a Personalized Greeting
Problem Statement: Write a Python program that:
1.  Takes a user's first name and last name as input.
2.  Concatenates the first name and last name into a full name.
3.  Prints a personalized greeting message using the full name.

   code- 
      fname = input("Enter your first name: ")     #takes first name from user
      lname = input("Enter your last name: ")      #takes last name from user
      name = fname + " " + lname                   #concatenates with a space in between fname and lname
      print(f"Hello, {name}! Welcome to the Python program.")  #used f formatting which can be used to print different datatypes

  output - Enter your first name: John
           Enter your last name: Doe
           Hello, John Doe! Welcome to the Python program.
