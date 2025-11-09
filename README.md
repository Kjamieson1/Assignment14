### Nanate-gumi: A Samurai Adventure
Name: Kenneth Jamieson
Course: CSC325
Game title: Nanate-gumi

## Summary
Nanate-gumi is a text based, multithreading adventure in order to show advenced OOP and concurrency in Java. There are three different characters Hayami Norihasa, Nakagawa Kiyohide or Akashi Takenori which are operating concurrently. Each are within its own threads with there own unique goals, abilities, and story events. This world has shared resources with event logs and treasures. 

## Technologies used

# Languages
JavaSE-25

# Libraries
java.util.concurrent
java.util.stream
java.util
java.time

# Frameworks: 
None

## Setup Instructions
1. Clone Repository
2. Compile the Code
3. Run the Game

## API
https://the‑trivia‑api.com/v2/questions
Filter for Japanese history content.
Pick and midify ones to fit game.

## Method Level Doc
Class/ Method/ Description/ Usage

GameCharacter/ act()/ Defines the main actions of the charaacter/ overridden in subclass, Runs in its own thread.
GameCharacter/ interact()/ Handles the main actions of the charaacter/ May access sharded resources. 
GameCharacter/ run()/ Entry for the thread./ calls act90 in a loop. 