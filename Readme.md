# Tic-Tac-Toe Game

A simple Tic-Tac-Toe game written in Python using Jupyter Notebook.

## Features

* Play against another player using the same keyboard
* Play against the computer
* Prevents moves on occupied spaces
* Automatically checks for a winner
* Displays the game board after each move

---

# Python Jupyter Notebook Setup Guide

This repository contains resources and instructions for setting up Python and Jupyter Notebook for development and learning purposes.

## Prerequisites

### Install Python

Download and install the latest version of Python:

https://www.python.org/downloads/

Verify the installation:

```bash
python --version
```

## Installing Jupyter Notebook

Install Jupyter Notebook using pip:

```bash
pip install jupyter
```

Launch Jupyter Notebook:

```bash
python -m notebook
```

If the `jupyter` command is not recognized on Windows, use:

```bash
python -m notebook
```

or

```bash
py -m notebook
```

## Alternative: Install Anaconda

Anaconda includes Python, Jupyter Notebook, and many useful data science libraries.

Download Anaconda:

https://www.anaconda.com/download

---

## Running the Tic-Tac-Toe Project

### Open Jupyter Notebook

Start Jupyter Notebook:

```bash
python -m notebook
```

Open the notebook file:

```text
tic_tac_toe.ipynb
```

Run all cells:

```text
Kernel → Restart & Run All
```

### Play the Game

When prompted, choose:

```text
c
```

to play against the computer, or

```text
f
```

to play against another player.

Enter a number from 1–9 to place your symbol on the board.

Board positions:

```text
1 | 2 | 3
---------
4 | 5 | 6
---------
7 | 8 | 9
```

### Example

```text
Would you like to play against the computer or friend? (c or f): c

Choose your space between 1-9: 5

 | |
-----
 |X|
-----
 | |
```

---

## Project Structure

```text
tic-tac-toe/
│
├── tic_tac_toe.ipynb
├── README.md
```


## Technologies Used

* Python
* Jupyter Notebook
* Anaconda
* Pip

## Author

Ricardo Jr Liera


