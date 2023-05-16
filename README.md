# Day 17: Quiz Game

This is the Day 17 project of the 100 Days of Python coding challenge. The Quiz Game is a command-line program that presents users with a set of True or False questions from the Open Trivia Database (OpenTDB)[https://opentdb.com] API. The program keeps track of the user's score and progress throughout the game.


## How to Run the Program

Clone the repository to your local machine.
+ Install the required packages listed in the requirements.txt file by running the command ```pip install -r requirements.txt``` in your terminal.
+ Run the quiz_game.py file in your terminal by running the command python quiz_game.py.


## How to Play the Game

+ Once the program is running, it will retrieve a set of random **True** or **False** questions from the (OpenTDB)[https://opentdb.com] API and present the first question to the user.
The user must answer the question by typing either "True" or "False" (Non case-insensitive).
+ If the user's answer is correct, the program will increment the user's score and move on to the next question. 
+ If the user's answer is incorrect, the program will move on to the next question without incrementing the user's score.
+ The program will continue to present questions until all questions have been answered.
+ Once all questions have been answered, the program will display the user's final score and the number of questions answered.

A test version is available on (Replit)[https://replit.com/@labelisaiah/Day17-Quiz-Game?v=1]


## API Information

The Open Trivia Database (OpenTDB)[https://opentdb.com] API is used to retrieve a set of random **True** or **False** questions for the quiz game. The API provides questions from a wide range of categories and difficulties. The question_data.py file contains a list of questions that were retrieved from the API during the development of this project. The questions are randomly selected from different categories and difficulties and are meant to provide a representative sample of the types of questions that can be retrieved from the API.

## Acknowledgments

This project was inspired by the 100 Days of Python coding challenge by Dr. Angela Yu. The Open Trivia Database (OpenTDB) API was used to retrieve the questions for the quiz game.
