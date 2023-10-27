# Structures-Functions
A. Structures The program helps in managing employee records using a structure

Algorithm:

Define a structure named 'employee' with the following members:

'name' (character array) to store the employee's name.
'age' (integer) to store the employee's age.
'salary' (floating-point) to store the employee's salary.
'dept' (character array) to store the employee's department.
Create an array of 'employee' structures named 'emp' with a maximum capacity of 100 records.

Prompt the user to enter the number of records 'n'.

Use a 'for' loop to input employee details for 'n' records: a. Display "Employee i" (i is the index of the current employee). b. Prompt the user to enter the employee's name and store it in 'emp[i].name'. c. Prompt the user to enter the employee's age and store it in 'emp[i].age'. d. Prompt the user to enter the employee's salary and store it in 'emp[i].salary'. e. Prompt the user to enter the employee's department and store it in 'emp[i].dept'.

Display "Records" to indicate the start of record printing.

Use a 'for' loop to print the employee records: a. For each employee record 'i': i. Display "Employee i". ii. Print the employee's name, age, salary, and department from 'emp[i]'.

End of the program.

B. Swap number using functions
Algorithm :

Create integer variables 'c' and 'd' to store two numbers.

Prompt the user to enter the value of 'c' and store it.

Prompt the user to enter the value of 'd' and store it.

Create integer pointers 'cp' and 'dp' and initialize them to point to 'c' and 'd' respectively.

Display "Original numbers - c = *cp, d = *dp".

Call the 'swap' function and pass 'cp' and 'dp' as arguments to swap the values pointed to by 'cp' and 'dp'.

Display "Swapped numbers - c = *cp, d = *dp".

Create a 'swap' function that takes two integer pointers 'a' and 'b' as parameters: a. Create a temporary integer variable 't'. b. Assign the value pointed to by 'a' to 't'. c. Assign the value pointed to by 'b' to 'a'. d. Assign 't' to the value pointed to by 'b'.

End of the program.

C. Class and Function
The program defines a cube class to calculate the volume of a cube based on user inputs for its dimensions.

Algorithm:

Create a class named 'cube' to represent a cube: a. Declare three public member variables: 'height', 'width', and 'length' to store the cube's dimensions. b. Define a public member function 'volume()' to allow the user to input the cube's dimensions. c. Define a public member function 'calculator()' to calculate and print the cube's volume.

In the 'main()' function: a. Create an instance of the 'cube' class named 'c1'.

Call the 'volume()' method on 'c1': a. Display "Enter length - " and read the user input into the 'length' member variable. b. Display "Enter width - " and read the user input into the 'width' member variable. c. Display "Enter height - " and read the user input into the 'height' member variable.

Call the 'calculator()' method on 'c1': a. Calculate the volume of the cube using the formula: volume = height * width * length. b. Display "Volume - " followed by the calculated volume.

End of the program.
