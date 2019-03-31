# Sec2Lessons

Hey Rachel! Thank you for looking at my code :)

For Code Challenge/Lesson 29, these were the assignment instructions. This is in Ruby, built in CodeAnywhere. 

The ordinal of a number is the number that defines a thing's position in a series, such as first, second, or third. 
Our program will convert numbers like 1, 2, and 3 to ordinals like 1st, 2nd, 3rd, and so on.

Your program will accept user input and display information back to the user. 
This is a problem you may encounter when building real web applications.

So for example, given an input of 51, a message like That's the 51st item! should be displayed on the screen.

Here are some hints to get you started:

Prompt the user with the message "Enter a number."
Receive the user input and store it in a variable. You may want to convert the number to an integer at this step.
Lop off the right-most digit and store it in a variable. Hint: A trick you can use to lop off the right-most digit is to calculate the number's % 10. Examples: 51 % 10 = 1; 75 % 10 = 5
Depending on the right-most digit (equal to the input number modulo 10) that comes back, determine the suffix and display a message to the user.
If the right-most digit equals 1, the suffix should be st
Otherwise, if the digit equals 2, the suffix should be nd
Otherwise, if the digit equals 3, the suffix should be rd
Otherwise, the suffix should be th
Hint: Don't forget about unusual use cases like 11th, 12th, or 13th.
