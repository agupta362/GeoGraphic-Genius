**Geography Quiz Game 🌍**

A simple Java quiz game that tests your geography knowledge with multiple-choice questions!

## Features
- 3 difficulty levels (Easy, Medium, Hard)
- 10-second timer per question
- 6 lives system
- Score tracking
- Simple GUI interface
- Fun sound effects

## How to Run
  1. Make sure you have [Java installed](https://www.java.com)
  2. Download the project files
  3. Open terminal in the project folder
  4. Run these commands:
  
  ```bash
  # Compile the game
  javac src/geographicGame/*.java -d out/
  
  # Start the game
  java -cp out/ geographicGame.GameManagerGUI

  ## If You Want to Use Terminal
    1. Open terminal in the project folder
    2. Type these commands one by one:
    ```bash
    javac src/geographicGame/*.java -d out/
    java -cp out/ geographicGame.GameManagerGUI


## How to Play
  1) Click "Start Game" from the main menu
  2) Read each question carefully
  3) Click A/B/C buttons to answer
  4) Correct answers give points
  5) Wrong answers cost 1 life
  6)Try to reach Level 3, and try to answers all questions to win.
    PRO TIP: Quick Answers give Bonus Time!

   *You can click on the instructions tab before starting the game to know more about how to play.

Game Files
  -> easy_questions.txt: Simple questions
  
  -> medium_questions.txt: Medium difficulty
  
  -> hard_questions.txt: Tough questions
  
  -> Game Design.docx: My planning document


Troubleshooting
  1) If sounds don't work: Make sure .wav files are in src/geographicGame folder
  
  2) If questions don't load: Keep .txt files in main folder
  
  3) Can't start game: Check you have Java 17+ installed

📚 File Structure
GeoGenius/
├── src/
│   └── geographicGame/          # Source code
│       ├── GameManagerGUI.java  # Main entry point
│       ├── GameWindow.java      # Game logic
│       ├── Question.java        # Question data model
│       ├── QuestionBank.java    # Question loader
│       └── background.wav       # Sound effects (WAV format)
|       |--- incorrect/ correct.wav   
├── easy_questions.txt           # Level 1 questions
├── medium_questions.txt         # Level 2 questions
├── hard_questions.txt           # Level 3 questions
└── highscore.txt                # high scores list


