
# Word Rush - Console Word Finding Game

Word Rush is a console-based word finding game developed in Python. Players are presented with word definitions and must guess the corresponding word. They can choose to receive letters to make the game easier, but doing so will affect their overall score. The game features different difficulty levels, a scoring system based on time and letter usage, and a leaderboard to track player scores.

## Game Features

- Three game modes: Easy, Medium, and Hard, each with different word difficulty levels.
- Players are presented with a word definition and must guess the corresponding word.
- Limited time for each question, with the option to stop the timer.
- Players can request letters to help them guess the word, but this affects their overall score.
- Scoring system that calculates points based on the time taken and the number of letters received.
- Achievement system to reward players for their progress and encourage replayability.
- Leaderboard to compare scores with other players.

## Installation and Usage

1. Clone the repository or download the project files.

2. Ensure that Python 3.x is installed on your system.

3. Install the required dependencies by running the following command:

   ```
   pip install -r requirements.txt
   ```

4. Run the game by executing the following command in your terminal:

   ```
   python WordRush.py
   ```

5. Follow the on-screen instructions to play the game.

## Gameplay Instructions

1. Upon starting the game, you will be prompted to enter your name and select a game mode (Easy, Medium, or Hard).

2. Each question will provide a definition, and you must guess the corresponding word.

3. You can choose to request letters from the word to make it easier. However, keep in mind that receiving letters will affect your score.

4. If you want to stop the timer, you can enter "stop." But note that a new timer will start if you do so.

5. To see the current state of the word (revealed letters and asterisks for unrevealed letters), enter "show."

6. If you need to see the question again, enter "question."

7. Answer each question within the time limit. If you fail to do so, you won't receive any points for that question.

8. At the end of the game, your score will be displayed, and the leaderboard will be updated.

## Project Structure

The project is organized as follows:

- `WordRush.py`: The main Python script containing the game logic.
- `easy.csv`, `medium.csv`, `hard.csv`: CSV files containing word lists for each difficulty level.
- `scoreboard.csv`: CSV file to store player scores and update the leaderboard.
- `requirements.txt`: Text file listing the required dependencies.

## Data Files

The game uses CSV files (`easy.csv`, `medium.csv`, `hard.csv`) to store word lists for each difficulty level. Each file contains two columns: the word definition and the corresponding word. You can modify these files to customize the word lists for each difficulty level.

## Dependencies

The project requires the following dependencies:

- `csv`: Python's built-in CSV module for reading and writing CSV files.
- `random`: Python's built-in random module for generating random numbers and shuffling word lists.
- `time`: Python's built-in time module for measuring elapsed time during gameplay.

## Future Enhancements

- Addition of personalized word lists or multiple-choice questions to diversify gameplay.
- Implementation of more advanced scoring algorithms based on different factors.
- Integration with a database system to store player scores and achievements.
