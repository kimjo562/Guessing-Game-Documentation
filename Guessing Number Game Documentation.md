| Joseph Kim|
| :---          	|
| s198022       	|
| Mock Assessment: Number Guessing Game  |
| Number Guessing Game Documentation  |

## I. Requirements

1. Description of Problem
	- **Name**: Number Guessing Game 

	- **Problem Statement**: 
	Create a game using the C# programming language and make the computer guess the number that the user inputed.

	- **Problem Specifications**:  The game must include: Input for validated use before use into the console. Without Errors or Warnings.

2. Input Information
    - User input is needed to navigate and continue on the program.

3.  Output Information
    - **Number**: When the range is given, user input is needed for the computer what number is it trying to guess.
    - **Attempts**: Once the program and run and the computer has sucessfully guess it will print how many attempts it took before it got it right.
   

## II. Design
||
| :---          	|
|**Number Guess Diagram**
| ![Number Guess Diagram jpg](https://i.imgur.com/ThPOAHn.jpg)

Uses the two values to create a valid range for the computer to guess between. User then inputs the number to guess for the computer to find and loops until computer correctly guesses the number. At the end of the program, it will show how many attempts it took before getting it correct.
|
|:------------
|
| ![User Interface png](https://i.imgur.com/VHfEzjH.png)

Two values are set one low and one high to create a range, and then ask  a number for the computer to guess.
|
|:------------
|
| ![User Interface png](https://i.imgur.com/cZlAGNR.png)

When given a number a guess, the computer will try to guess and continue to loop until the computer has sucessfully found the correct number and the program will stop looping. It will show the amount of times it has looped as a way to print the amount of attempts taken.

2. ### Object Information

   **File**: Program.cs

     Description: The main body of the program and loops.
     
    **Attributes**

         Name: Random random = new Random();
             Description: Using the System Class to create a pseudo  random number generator and intializes it in a new instance.
             Type: public static

         Name: counter
             Description: The amount of times the program looped, acts as an attempt counter.
             Type: Integer

        Name: lowChoice
             Description: Hold the lowest number and uses it as part of the range.
             Type: Integer

        Name: highChoice
             Description: Hold the highest number and uses it as part of the range.
             Type: Integer

        Name: guessNumber
             Description: How the computer inputs its guess into the program using the random function.
             Type: Integer

        Name: guessChoice
             Description: The number between the range for the computer to guess. User inputted choice.
             Type: Integer

        Name: guessing
             Description: The continued use of guessing in a while loop until the computer guesses the correct number, then stop.
             Type: Bool

        Name: validation
             Description: checks if the user is putting a number within the boundries of range.
             Type: Bool
