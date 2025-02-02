# Weekly-Class-Scheduling-Using-Graph-Coloring

## Description
This project addresses the scheduling problem using edge coloring in graph theory. The goal is to generate an optimal weekly learning schedule for teachers and classes while ensuring that:
- A teacher does not teach multiple classes in the same period.
- A class does not have multiple teachers in the same period.

The solution is implemented in Python and utilizes libraries such as `networkx`, `numpy`, and `pandas` to construct and visualize the schedule.

## Features
- Generates a random session matrix for teachers and classes.
- Constructs a conflict graph based on scheduling constraints.
- Applies a greedy coloring algorithm to minimize scheduling conflicts.
- Distributes class sessions across five working days.
- Outputs the schedule in a tabular format.

## Requirements
Ensure you have the following libraries installed before running the script:

```bash
pip install networkx numpy pandas tabulate
```

## Usage
Run the script and provide the number of teachers and classes as input:

```bash
python schedule.py
```

Example Input:
```
Enter the number of teachers (m): 5
Enter the number of classes (n): 10
```

The program generates a weekly schedule and displays it in a readable table format.

## Contributors
- Hasna Rosyida Nur Adila
- Tria Sania Oktavia
- Ghaisan Zaki Pratama

## License
This project is licensed under the MIT License.


