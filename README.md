
# chijindu-py-suridata

## Overview

The `chijindu-py-suridata` program is a Python-based simulation of the classic game called "Dwarf and Giant." The goal of the game is to create unique pairs of employees, where each pair comprises a "Dwarf" and a "Giant."

## Game Description

In the game's context, each employee represents either a "Dwarf" or a "Giant." The program ensures fairness by pairing each employee exactly once as either a dwarf or a giant. The game's fairness lies in guaranteeing that every employee experiences both roles within the game.

## Features

- Unique Pair Generation: The program creates pairs of employees based on certain criteria to ensure uniqueness.
- Random Pair Assignment: Employees are randomly assigned as either dwarfs or giants for each pair, ensuring unpredictability.
- Data Cleaning: Duplicates within the employee dataset are removed to maintain a clean and accurate list of employees.

## How to Use

1. Input Data: The program requires a list of employees, each with three fields: name, department, and age.
2. Execution: Execute the main program or function to run the simulation.
3. Adjustment: Modify the `chunk_size` parameter as needed for multiprocessing.
4. Output: The program generates pairs of dwarfs and giants, displaying the final output list of paired employees.

## Usage Example

To run the program:

```bash
python main.py
```

## Requirements

- Python 3.x
- Standard Python libraries
- Multiprocessing module

## Author

- [Alozie Chijindu]
- [alozie59@live.com]
  
Feel free to contribute or provide feedback to enhance the program further.

---

