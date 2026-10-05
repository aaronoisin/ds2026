# Python practice: NumPy and pandas

Optional practice for anyone who wants more repetitions than the labs give you. Nothing
here is assessed.

## What is in here

| File | What it is |
|---|---|
| `numpy-exercises.ipynb` | About 50 short NumPy tasks, one per cell |
| `pandas-exercises.ipynb` | About 50 short pandas tasks, on a small car sales dataset |
| `*-solutions.ipynb` | The same notebooks with the answers filled in |
| `data/` | The three CSV files the pandas notebook reads |

## How to use it

1. Unzip this folder inside your `ds2026` folder, so you have `ds2026/python-practice/`.
2. Open `ds2026` in VS Code, as always, and open the exercise notebook from there.
3. Select your `.venv` as the kernel.
4. Work down the notebook. Each cell has a comment saying what to do and an empty line to
   do it on.
5. Look at the solutions when you are stuck, **after** you have tried. Reading a solution
   you have not attempted feels like learning and is not.

## Three cells are supposed to fail

Two in NumPy, one in pandas. They are there to show you an error and ask you to work out
why, so do not assume you have broken something:

- adding arrays of shape (3, 5) and (5, 3)
- taking the dot product of two (4, 3) arrays
- plotting a price column that is still text

## Fixed from last year

The pandas notebooks looked for `../data/car-sales.csv`, which did not exist. They now read
from `data/` next to the notebook, and the CSV files are included.
