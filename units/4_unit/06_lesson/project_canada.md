# Project 4: Tic-Tac-Toe

Using Python, students will create a Tic-Tac-Toe game. This project has 3 parts: 

1. Designing the game so that two users can play Tic-Tac-Toe against one another.
2. Creating a Tic-Tac-Toe checker which will check the board to see if Xs or Os have won the game. 
3. Enhancement:  replacing the Xs and 0s with two other characters, within another context!

## Overview
[Tic-Tac-Toe](http://www.merriam-webster.com/dictionary/tic-tac-toe) is a game in which one player draws X's and another player draws O's inside a set of nine squares and each player tries to be the first to fill a row, column, or diagonal of squares with either X's or O's. We will be writing an interactive Tic-Tac-Toe program. At the end of each turn the computer will check to see if X's have won the game or if the O's have won the game. 

### Behavior
* The program will prompt the user to enter their name and their opponents name. 
* Whoever enters their name first will be playing as X's, and the other player will be O's. 
* The players will take turns inputting the row and column they would like to place their mark. 
* If that spot is already taken the program will ask for the spot again. 
* At the end of each player's turn the program will check if that player has won.
* At the end of each player's turn the program will print the updated game board.
* If there are no more spots open and nobody has won the game, the program will print `Tie game!`.

### Implementation Details
* Use variables to store the user names for personalized prompts.
* Create a game board represented as a list of lists, size 3 by 3. 
***Note: This is a change from our earlier implementations of Tic-Tac-Toe. Why do you think this might be better?***
* Check for a winner horizontally, vertically, and on both diagonals.
* Cannot allow a user to overwrite a spot on the board.
* Use a constant value for the "X", and "O" character (so that future enhancements are easy!  See below.)

### Testing
* Create a document called a "test plan" to list out how you will test your game. 
* This should include all the test cases related to game play. 
* Before you "deliver" (or submit) your game, you should go through all the items on your test plan.
* Ask yourself:  As a User, what should they be able to do?  What is their goal?  What are the possible inputs?
* A helpful template is this sentence:  "As a User, I want to ..., so that I can ..."
* A test plan should include going through all the goals/tasks, and see if they are achieved. 
* A test plan should include trying bad, or un-intended, input.  How does your game respond?

---
#### Emphasize with students...

#### Curriculum Competencies - Applied Design, Testing

In this project, we are creating a familiar game.  Nonetheless, it is wise to create a test plan, even before implementation begins. 
As the students progress, they should refer back to their plan to stay focussed on tasks/features of the game. 

Software developers aim to have "something" working at the end of each iteration (or sprint).  In other words,
some item in the test plan has been tested successfully.   At the end of an iteration / milestone, consider inviting peers 
(or family and friends) to try out your game, even if not everything is working yet.  In the process, developers can gain
insight and feedback to help their next iteration.   User testing and feedback that is woven into the subsequent iteration is core
to a successful agile project management process. 

---

---
#### Emphasize with students...

#### Curriculum Competencies - Applied Design, Sharing

Have a game day party!  Invite others to come to your classroom.  Send your game to friends.  Create a few user experience survey 
questions to gather from anyone, and everyone, who plays your game.   Ask questions related to anything that may help your
next iteration:  colour, size, font, layout, game play, words of encouragement (or lack of!), intuitiveness, and so on. 

---

### Enhancments
* Now that you have a basic version created, how can it be made unique?
* Consider aspects that the design that be changed so that the game can have a fresh look/feel?
* Consider context that is relevant to your community, or daily life.  
* Instead of X's and O's, for example:
    * If you live by the West Coast, you can use:  B (beach) or M (mountain)
    * If you have multi-cultural community, you can use: 是 (yes) 否 (no) 
    * If you are into emoticons, you can use:  😍 or  😭
    * Find two animals that are hunted by the First Nations people in your area.

---
#### Emphasize with students...

#### Curriculum Competencies - Applied Design, Ideating

A simple game like Tic-Tac-Toe can bring on new life when applied to a new context.  
It can be used to bring awareness to current issues or interests in our daily life. 
Aside from the entertainment value associated with the game, software enables use to communicate other purpose and intentions. 
Be creative!

---

---
#### Emphasize with students...

#### Curriculum Competencies - Applied Technologies

Characters we see on the screen (console) are simply digital encodings of 0's and 1's.  
When we print characters in Python or any other language, we are using the ascii 
or unicode encodings.  Students can explore and use these codes in their Python print statement.  Emojis: https://www.geeksforgeeks.org/python-program-to-print-emojis/
Other language characters:  https://realpython.com/python-encodings-guide/ 

---

## Grading 
### Scheme/Rubric
| **Functional Correctness (Behavior)**                                |     |
| --------------------------------------------------------------- |-----|
| Program prompts user for name | 2   |
| Program marks board where user requested| 5|
| Program prints a readable board after user's turn| 5|
| Program won't overwrite value on board | 5   |
| Program reports who won or if there was a tie             | 15  |
| Program ends after win, loss, or tie       | 3  |
| **Sub total**                                                   | 35  |
| **Technical Correctness   **                                    |     |
| Correct use of game loop                                        | 5  |
| Correctly indexes into lists of lists to store board            | 5  |
| Correctly check board for mark                                  | 5  |
| Check for winners on all three horizontals and verticals        | 20  |
| Checks for winners on both diagonals                            | 10  |
| **Sub total**                                                   | 45  |
| **Total**                                                       | 80 |


