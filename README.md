# 10_Day_Loops

This is my solution to the 10 Days of Loops challenge, inspired by [30 Days of Python](https://github.com/Asabeneh/30-Days-Of-Python).

## Day 12 — Country Data Analysis

Working with a real-world dataset containing information about countries — capitals, languages, populations, and currencies.

### Exercises

**Exercise 1:** Find the total number of unique languages in the data

**Exercise 2:** Find the 10 most spoken languages across all countries

**Exercise 3:** Find the 10 most populated countries in the world

### Data

The dataset is stored in the `data/` folder as `countries_data.py`.

## How It Works

The core approach is straightforward. Languages are collected into both a list and a set — the list tracks frequency, the set tracks uniqueness. Tuples are then used to pair counts with names, making sorting simple and clean. The same pattern applies to population ranking.

## What I Learned

Working through this helped me get more comfortable with Python data structures like sets, lists, and tuples. I also practiced using f-strings for formatted output and learned how sorting tuples works in Python.

## Run It Yourself

Clone the repo and run:
```bash
git clone https://github.com/ttt081/10_Day_Loops.git
cd 10_Day_Loops
python loop10.py
```

No external libraries needed — just pure Python.


## Author

[ttt081](https://github.com/ttt081)
