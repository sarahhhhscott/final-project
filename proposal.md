The name of my project is RPS Bot.


DESCRIPTION AND FEATURES
The objective of my project is to create a program that will play rock paper scissors with the user. 
In doing so, it will prompt the user for an input on what they decide to choose for the match. 
Next, it will say something like "Answer confirmed. Playing now:". 
Then, it will go "Rock, Paper, Scissors, Shoot!" with time in between each word.
The next text would be "[insert bot name] chose [random choice]! You [win/lose]!
The match would repeat three times. After the third time it will count the wins or losses from the player and bot and determine the victor.
After stating the victor, it will say something like: "Thanks for playing! Want to play again?"
If the user returns yes, it will play again. If the user returns no, then it will say something like, "See you next time!"
I debated on creating a display screen to play the game, but I would most likely have to implement that with the pygame library, which I do not feel comfortable doing a project of this significance with due to my severe inexperience with its library. If I do have any time, I may be able to try it out, but for now, this code is set to be executed within the terminal.


OUTCOME
The process above is the desired outcome of my project. The minimum outcome is to at least generate a response with the user's input to still be able to play rock paper scissors with the bot.


PROCESS
I plan to execute the timing of the print statements with the clock.tick function. As for the generated choices, I may either store them in a dictionary or its own defined function. The randomness of the choice will be implemented by importing random.


CHALLENGES
I believe the main challenges for this project will be to create the right timing in between print statements and to debug the code. I am sure I will run into errors with this project which might be a bit harder to solve as I preict this will be a rather lengthy amount of code.


MILESTONES
Some of my weekly milestone goals to track will be just aiming to finish one aspect of my desired outcome per week, such as: implementing text, generating prompts, calculating timing and so on.