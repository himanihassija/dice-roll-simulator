# dice-roll-simulator
A Python-based dice roll simulator that supports multiple dice rolls, tracks roll statistics, and displays frequency analysis using clean and modular code.
# Dice Roll Simulator (Python)

A command-line based dice roll simulator built in Python. The project simulates rolling two dice, calculates totals, tracks roll statistics, and displays frequency analysis for each dice face. This project focuses on writing clean, reliable code with proper input handling and basic statistical tracking.

## Features
- Simulates rolling two six-sided dice
- Displays individual dice values and their total
- Tracks the total number of rolls
- Maintains frequency count for each dice face
- Allows repeated rolls until the user exits
- Clean and beginner-friendly code structure

## Technologies Used
- Python 3
- Standard Library (random module)

## Demo
https://github.com/himanihassija/dice-roll-simulator/blob/main/dice%20roll%201.JPG
https://github.com/himanihassija/dice-roll-simulator/blob/main/dice%20roll%202.JPG

## Project Structure
dice-roll-simulator-python/
├── dice_simulator.py
└── README.md

## How It Works
1. The program waits for user input.
2. Pressing Enter rolls two dice.
3. The values of both dice and their sum are displayed.
4. Each roll updates the frequency count.
5. Typing q exits the program and displays a summary.

## Sample Output
Dice Roll Simulator
--------------------
Press Enter to roll the dice or type 'q' to quit:

Die 1: 3, Die 2: 5
Total: 8

Press Enter to roll the dice or type 'q' to quit:

Game Summary
------------
Total rolls: 4
Frequency of each face:
1: 2
2: 1
3: 3
4: 0
5: 1
6: 1

## How to Run
1. Make sure Python 3 is installed.
2. Clone the repository:
   git clone https://github.com/your-username/dice-roll-simulator-python.git
3. Navigate to the project directory:
   cd dice-roll-simulator-python
4. Run the program:
   python dice_simulator.py

## Possible Enhancements
- Add ASCII representations of dice faces
- Store roll history in a file
- Visualize frequency using graphs
- Convert the project into a GUI application
- Refactor using object-oriented programming

## Learning Outcomes
- Working with random number generation
- Using loops and conditional logic
- Managing data with dictionaries
- Writing structured and readable Python code

## License
This project is open-source and available under the MIT License.
