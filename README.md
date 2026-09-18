# Miniproject1
First mini project - Blackjack

🃏 Blackjack Game

A simple Blackjack game developed in Python as a programming practice project.

The game allows the player to play Blackjack against a dealer, choose between Hit and Stand, draw cards from a deck, calculate scores, and keep track of the overall score across multiple rounds.

🎮 How the Game Works

At the beginning of the game, the player enters their name and chooses whether they want to play.

During each round:

A new deck of 52 cards is created.
The player receives two cards.
The dealer receives cards according to the game logic.
The player can choose:
Hit → receive another card.
Stand → stop receiving cards.
The dealer continues drawing cards while their score is below 17.
Scores are calculated.
The winner of the round is determined.
The game keeps track of the player's and dealer's total points.
The player can choose to play another round.
🃏 Card Values

The cards are represented as follows:

Card	Value
2–10	Face value
J	10
Q	10
K	10
A	11

Note: The current version treats an Ace as 11 and does not yet dynamically change its value to 1 when necessary.

🧠 Main Features
Random card distribution
52-card deck generation
Player and dealer score calculation
Hit / Stand decisions
Dealer behaviour based on score
Bust detection
Multiple rounds
Score tracking between rounds
Input validation
Delays using time.sleep() to create a more game-like experience
Simple command-line interface
🛠️ Technologies

This project was built using:

Python
random — for randomly selecting cards
time — for adding delays between game events

No external libraries are required.

📂 Project Structure

The project is currently contained in a single Python file.

The main functions are:

create_cards_deck()

Creates a standard 52-card deck.

def create_cards_deck():
    return (list(range(2, 11)) + ['J', 'Q', 'K', 'A']) * 4
score_calculate(cards)

Calculates the score of a player's or dealer's hand.

def score_calculate(cards):
    ...
▶️ How to Run

Make sure Python is installed on your computer.

Clone the repository:

git clone YOUR_REPOSITORY_URL

Navigate to the project folder:

cd YOUR_PROJECT_FOLDER

Run the game:

python blackjack.py
📚 What I Practiced

This project was created as a way to practice fundamental Python programming concepts, including:

Variables
Strings and integers
Lists
Dictionaries
Functions
if / elif / else
while loops
for loops
List operations
Randomisation
User input
Input validation
Exception-free control flow
Boolean values
State management
Function return values

It also helped me practice breaking a larger problem into smaller programming tasks.

🚀 Possible Future Improvements

Some ideas for future versions:

Hide one of the dealer's cards until the player's turn is finished

Improve the code structure by separating the game into smaller functions

Add automated tests

Improve input validation

Add more detailed game statistics

👩‍💻 About the Project

This is a learning project created to practice Python programming and develop problem-solving skills through a small playable game.

The project focuses on understanding programming fundamentals and gradually improving code structure as new concepts are learned.