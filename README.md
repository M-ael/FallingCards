# FallingCards
A simple website that allows you to enter flashcards in a CSV format and play a game in order to memorize them through active recall. 

During the game, notes with the terms of randomly chosen flashcards fall down inside the canvas until they hit the bottom edge. Your job is to input and send (`enter`) the corresponding definition before the note hits the bottom - if that happens, you lose.

- Correct definitions delete their corresponding term's note.
- The game can be paused by holding the square above the canvas for around a second.

This game is most useful for memorizing flashcards with short definitions, like word translations (ex: `Term: "the dog", Definition: "le chien"`), or names/labels (ex: `Term: "Capital of France", Definition: "Paris"`).

## Usage
Open the deployment on github-pages or install and run the project locally.

## Installation
Since this project is very simple, its installation is uncomplicated.

#### 1. Clone the repository:

Open your desired location in the terminal and run
```
git clone https://github.com/M-ael/fallingcards.git
```
Or click "Code", download the zip file, and extract it to your desired location. 

#### 2. Open the page or run a local server.
Double-click `index.html` or open an IDE (like VSCode) and run a local server (using the "Live Server" extension, for example).