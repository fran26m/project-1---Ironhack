# project-1---Ironhack
First project - DA Bootcamp - Ironhack

# Blackjack (Simplified)

## Project Overview

This project is a simplified version of the Blackjack card game developed in Python as part of a Data Analytics Bootcamp.

The player competes against the dealer and attempts to achieve a higher score without exceeding 21.

## Game Rules

* The player starts with two cards.
* The dealer starts with two cards.
* Number cards keep their value.
* J, Q and K are worth 10.
* Ace is worth 11.
* The player can choose to:

  * **Hit**: receive another card.
  * **Stand**: stop receiving cards.
* The dealer must continue drawing cards until reaching a score of 17 or higher.
* The winner is determined by comparing the final scores.

## Features

* Deck of cards stored in a list.
* Game state stored in a dictionary.
* Input validation for player decisions.
* Automatic dealer logic.
* Score tracking for both player and dealer.
* Display of player and dealer hands throughout the game.

## Assumptions

* All dealer cards are visible.
* If the player and dealer finish with the same score, the game ends in a tie.
* Cards are not removed from the deck after being dealt.

## Technologies Used

* Python
* Lists
* Dictionaries
* Loops
* Conditional statements
* Functions
* Random module

## Learning Objectives

This project was created to practice:

* Data structures
* Flow control
* Functions
* Game logic design
* Input validation
* Problem-solving in Python

## Author

Juan Francisco Orona
