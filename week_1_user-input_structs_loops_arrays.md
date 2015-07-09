# Week 1:
## User Input, Structs, Loops, Arrays  

### Review Questions:

- Which function is used to write output to the console?
- Which function is used to read input from the console?
- Which keyword can we use to create a user-defined type?
- Which type of loop will run as long as a condition is true?
- Which keyword is used to stop a loop from executing?
- Which type of loop runs until its termination condition is true?
- Which keyword can we use to skip to the next iteration of a loop?
- Which data structure is used to stored elements of the same type?
- What is the name of a user-defined type that can be defined


### Excercises:
#####*These exercises will test the concepts that we covered in class.*

- Write a program that prints the numbers 1 through 10 using a loop.
- Write a program that prints the numbers 1 through 10 using a different kind of loop.
- Write a program that takes in an **int** n and prints the numbers 1 through n.
- Write a program that takes in an **int** n and prints the even numbers 2 through n.
- Write a program that prints the sum of 1 through 10 using a loop.
- Write a program that takes in an **int** n and prints the sum of the numbers 1 through n using a loop.
- Use the program you wrote in the previous exercise to print the sum of the numbers from 1 through 10000.
- Write a program that takes in an **int** n and a **String** s and prints out s on its own line, n times. If n is negative,   print "" (that is print an empty sring).
- Modify the method to print out the string concatenated with itself n times.
- Write a program that prints the first ten [Fibonnaci numbers](https://www.mathsisfun.com/numbers/fibonacci-sequence.html).
- Modify the program to sum the first ten Fibonnaci numbers.
- Modify the program to take in an `int` n and sum the first n Fibonnaci numbers.
- Write a program that stores information about a shape in a **struct** called shape. The struct should hold information       about the type of shape it is and it's color.

### Challenging Exercises: 
#####*Once you have finished all of the above exercises you can try to complete some of the following more challenging exercises.*

- Write a program that asks the user to type the width and the height of a rectangle and then outputs to the screen the area   and the perimeter of that rectangle.

- Write a program which accepts five numbers from user input and then outputs how many numbers were read and the minium and    maximum value of all the numbers.
  ```
      Example Run:  
      1 99 5 19 -23   
      Min value: -23  
      Max value: 99  
  ```

- "99 Bottles of Beer" is a traditional song in the United States and Canada. It is popular to sing on long trips, as it has   a very repetitive format which is easy to memorize, and can take a long time to sing. The song's simple lyrics are as        follows:

  > "99 bottles of beer on the wall, 99 bottles of beer.  
  > Take one down, pass it around, 98 bottles of beer on the wall."  
    
  The same verse is repeated, each time with one fewer bottle. The song is completed when the singer or singers reach zero.  
  Your task here is write a program capable of generating all the verses of the song.

- Define a function generate_n_chars() that takes an integer n and a character c and returns a string, n characters long,      consisting only of c’s. For example, generate_n_chars(5,"x") should return the string "xxxxx".   

- Write a program that obtains a students name, age and GPA from user input and stores them into a **struct** and then         outputs that information to the consoloe.
    - Exammple Run:

  ```
    Enter name: Adele
    Enter age: 21
    Enter GPA: 334.5
    
    Displaying Information
    Name: Adele
    Age: 21
    GPA: 4.0
  ```
