# Review questions and exercises for Unit 0: Weeks 0-3.

| Dates       | Week| Topics Covered    |
|:-----------:|:---:|:------------------|
| Jun 2 - 7   | 0   | [Variables, Types, and Conditional Statements] (https://github.com/accesscode-2-2/Exercises/blob/master/week-0_variables_types_conditionals.md)|
| Jun 9 - 14  | 1   | [User Input, Structs, Loops, Arrays] (https://github.com/accesscode-2-2/Exercises/blob/master/week_1_user-input_structs_loops_arrays.md)|
| Jun 16 - 21 | 2   | [Bubble Sort, Functions, Review Objects, Pairing Objects] (https://github.com/accesscode-2-2/Exercises/blob/master/week_2_bubble_sort_functions_review_objects_pairing_objects.md)|
| Jun 23 - 28 | 3   | [Classes, NSArray, NSMutable Array] (https://github.com/accesscode-2-2/Exercises/blob/master/week_3_classes_nsarray_nsmutable-array.md)|

### Easy:

Write a program that asks the user to type the width and the height of a rectangle and then outputs to the screen the area and the perimeter of that rectangle.

Write a program that asks the user to type 5 integers and writes the average of the 5 integers. This program can use only 2 variables.  

Write a program that asks the user to type 2 integers A and B and exchange the value of A and B.  

Write a program which asks for a student score. Score is a number from 0-100. Translate the score into grade according to the next limits:  

    score >= 90 ==> "A"  
    score >= 80 ==> "B"  
    score >= 70 ==> "C"  
    score >= 60 ==> "D"  
    anything else ==> "F"  
    If the score is 100 print "Perfect score!"

Write a program that asks the user to type an integer and writes "YOU WIN" if the value is between 56 and 78 (both included). In the other case it writes "YOU LOSE".  

Write a program that asks the user to type all the integers between 8 and 23 (both included) using a for loop.  

Write a program that asks the user to type 10 integers of an array. The program must compute and write how many integers are greater than or equal to 10.    

Write a program with a function that takes two int parameters, adds them together, then returns the sum. The program should ask the user for two numbers, then call the function with the numbers as arguments, and tell the user the sum.  

Write a program which accepts numbers as arguments and which determines the lowest and highest number.  
```
    Example Run:  
    1 10 99 5 19 -23 17  
    Read 7 numbers  
    Min value: -23  
    Max value: 99  
```
Define a function max() that takes two numbers as arguments and returns the largest of them.   

Define a function max_of_three() that takes three numbers as arguments and returns the largest of them.  

The function max()  and the function max_of_three() from will only work for two and three numbers, respectively. But suppose we have a much larger number of numbers, or suppose we cannot tell in advance how many they are? Write a function max_in_array() that takes an array of numbers and returns the largest one.  

Define a function that computes the length of a given list or string.   

Write a function that takes a character and returns True if it is a vowel, False otherwise.  

Write a function translate() that will translate a text into "rövarspråket" (Swedish for "robber's language"). That is, double every consonant and place an occurrence of "o" in between. For example, translate("this is fun") should return the string "tothohisos isos fofunon".  

Define a function sum() and a function multiply() that sums and multiplies (respectively) all the numbers in an array.. For example, sum([1, 2, 3, 4]) should return 10, and multiply([1, 2, 3, 4]) should return 24.  

Define a function reverse() that computes the reversal of a string. For example, reverse("I am testing") should return the string "gnitset ma I".  

Define a function is_palindrome() that recognizes palindromes (i.e. words that look the same written backwards). For example, is_palindrome("radar") should return True.  

Write a function is_member() that takes a value (i.e. a number, string, etc) x and an array of values a, and returns True if x is a member of a, False otherwise.  

Define a function overlapping() that takes two arrays and returns True if they have at least one member in common, False otherwise. You may use your is_member() function. (Hint: Write it using two nested for-loops.)  

Define a function generate_n_chars() that takes an integer n and a character c and returns a string, n characters long, consisting only of c’s. For example, generate_n_chars(5,"x") should return the string "xxxxx".   

Define a function histogram() that takes a list of integers and prints a histogram to the screen. For example, histogram([4, 9, 7]) should print the following:
```
    ****
    *********
    *******
```

Write a version of a palindrome recognizer that also accepts phrase palindromes such as "Go hang a salami I'm a lasagna hog.", "Was it a rat I saw?", "Step on no pets", "Sit on a potato pan, Otis", "Lisa Bonet ate no basil", "Satan, oscillate my metallic sonatas", "I roamed under it as a tired nude Maori", "Rise to vote sir", or the exclamation "Dammit, I'm mad!". Note that punctuation, capitalization, and spacing are usually ignored.  

A pangram is a sentence that contains all the letters of the English alphabet at least once, for example: The quick brown fox jumps over the lazy dog. Your task here is to write a function to check a sentence to see if it is a pangram or not.  

"99 Bottles of Beer" is a traditional song in the United States and Canada. It is popular to sing on long trips, as it has a very repetitive format which is easy to memorize, and can take a long time to sing. The song's simple lyrics are as follows:

  > 99 bottles of beer on the wall, 99 bottles of beer.  
  > Take one down, pass it around, 98 bottles of beer on the wall.  
    
The same verse is repeated, each time with one fewer bottle. The song is completed when the singer or singers reach zero.  
Your task here is write a program capable of generating all the verses of the song.  

Define a simple "spelling correction" function correct() that takes a string and sees to it that 1) two or more occurrences of the space character is compressed into one, and 2) inserts an extra space after a period if the period is directly followed by a letter. E.g. correct("This   is  very funny  and    cool.Indeed!") should return "This is very funny and cool. Indeed!"   

The third person singular verb form in English is distinguished by the suffix -s, which is added to the stem of the infinitive form: run -> runs. A simple set of rules can be given as follows:  
    - If the verb ends in y, remove it and add ies  
    - If the verb ends in o, ch, s, sh, x or z, add es  
    - By default just add s  
Your task in this exercise is to define a function make_3sg_form() which given a verb in infinitive form returns its third person singular form. Test your function with words like try, brush, run and fix. Note however that the rules must be regarded as heuristic, in the sense that you must not expect them to work for all cases. Tip: Check out the string method.  

Challenging:  

Define a function overlapping() that takes two arrays and returns True if they have at least one member in common, False otherwise. (Hint: Try using two nested for-loops.)  

Write a program which simulates one or more dice with values from 1 to 6. The program takes a single argument which is the number of dice. The output should contain the values of the dice and the probability for this combination to occur. The probability is expressed as a decimal value between 0 and 1 with three decimal points. Extend the program so that it can roll dice with any number of sides.  
``` 
    Example Run:  
    3  
    Rolling 3 dice ...  
    4 2 8 (Probability: 0.473)  
```

A goat, a wolf and a salad are on one side of a river and you need to get them to the other side using your boat. You can carry one item in your boat to the other side at any given time. However, when the goat and the wolf are left alone the wolf will eat the goat. If the goat and the salad are left alone the goat will eat the salad. As long as you are with them nothing will happen, i.e. the wolf won’t eat the goat and the goat won’t eat the salad. Write a program which determines algorithmically an order in which you carry them all to the other side.  
