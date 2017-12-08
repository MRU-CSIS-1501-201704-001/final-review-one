# Lab 05 - More While Loop Practice

## What this lab gets you

* Opportunities to practice working with the following Java concepts:
    * counted while loops
    * sentinel while loops
    * `Random`  

## Getting Ready

One partner is the _driver_ - they will be at the keyboard, doing the coding. The other person is the _navigator_ - their job is to watch what's going on, catch any mistakes the driver might be making, make suggestions if the driver gets stuck, and ask questions if they don't understand what the driver is doing.

1. Create a new BlueJ project named something that captures the usernames of both partners. (like **fnord388-sjers888-project**)

---

## Programming Practice 1

1. Create a new class in the project called `AreWeThereYet`.
1. Create a standard Java main in that class.
1. Create code that solves the following problem:

    _Parents the world over dread the question: Are we there yet? Create a program that continually asks "Are we there yet?". If the user types in y or yes (any case), the program will stop after printing "Yay!"; if the user types in n or no (any case), the program asks the question again; otherwise, the program says "What?" - and asks the question again._

    _Here is a run of the program:_

        Are we there yet?
        > n
        Are we there yet?
        > nO
        Are we there yet?
        > don't make me come back there
        What?
        Are we there yet?
        > y
        Yay!


Make sure your output looks similar to that shown - the prompt should be `> `.

When you think you have completed the task, call your instructor over.

---

## Programming Practice 2

Switch driver and navigator.

1. Use the same project.
1. Create a new class in the project called `BlintzButler`.
1. Create a standard Java main in that class.
1. Create code that solves the following problem:

    _Blintzes, as you well know, are tasty. We want to make a program that gives us blintzes until we run out._

    _Make a program that first asks how many blintzes we have in the house. It should then keep asking "How many blintzes would you like, ma'am (or sir)?" until all the blintzes are gone._
    
    _If we ask for a valid number of blintzes, it should print "Very good, ma'am - here are your [number] blintzes. Enjoy." If we ask for more blintzes than we have left, it should say "Regretfully, we currently don't have that many blintzes. We have [number left]." and then ask the question again. Once we are out of blintzes, it should print "I regret to inform you that we no longer have any blintzes remaining."_

    _Here is an example run:_

        Please enter the number of blintzes in the house: 8

        How many blintzes would you like, ma'am? 9
        
        Regretfully, we currently don't have that many blintzes. We have 8.

        How many blintzes would you like, ma'am? 3

        Very good, ma'am - here are your 3 blintzes. Enjoy.

        How many blintzes would you like, ma'am? 6

        Regretfully, we currently don't have that many blintzes. We have 5.

        How many blintzes would you like, ma'am? 5

        Very good, ma'am - here are your 5 blintzes. Enjoy.

        I regret to inform you that we no longer have any blintzes remaining.


You can assume that the user will only enter integers.

When you think you have completed the task, call your instructor over.

---

## Programming Practice 3

Switch driver and navigator.

1. Use the same project.
1. Create a new class in the project called `WordMixMaster`.
1. Create a standard Java main in that class.
1. Create code that solves the following problem (adapted from Horstmann E4.7):

    _Create a program that creates a word jumble, following this algorithm:_

        Read a word with length >= 3 (re-prompt if necessary) 
        Repeat word.length() times  
            Pick a random position i in the word that is not the last position
            Pick a random position j > i in the word
            Swap the letters at positions i and j
        Print the word  

When you think you have completed the task, call your instructor over.

---

## Programming Practice 4

Switch driver and navigator.

1. Use the same project.
1. Create a new class in the project called `BlintzButlerRefined`.
1. Create a standard Java main in that class.
1. Create code that solves the following problem:

    _Your blintz butler was so awesome, the public is clamouring for more. You've decided to improve the program by adding the following additional features:_

    * If the user enters in a non-integer, the program will print "Ma'am? (or Sir?)" and then re-prompt.
    * If the user enters a 0, the program will print "Feeling unwell, ma'am? Perhaps another blintz might help." and then re-prompt.
    * If the user enters a negative number, the program will print "How droll." and then re-prompt.

    _Here is an example run of the improved program:_

        Please enter the number of blintzes in the house: 3

        How many blintzes would you like, ma'am? Avast there!
        
        Ma'am?

        How many blintzes would you like, ma'am? 0

        Feeling unwell, ma'am? Perhaps another blintz might help.

        How many blintzes would you like, ma'am? -4

        How droll.

        How many blintzes would you like, ma'am? 3

        Very good, ma'am - here are your 3 blintzes. Enjoy.

        I regret to inform you that we no longer have any blintzes remaining.