# netflix-1990s-movie-analysis
# Chart Show
![Figure_1](https://github.com/user-attachments/assets/bf1a294a-bb1b-4dea-b085-7645559f1c83)


This repository contains two Python code files that analyze Netflix movie data from the 1990s. The analysis includes:
- Filtering movies released in the 1990s.
- Finding the most frequent movie duration.
- Counting the number of short action movies (movies with a duration of less than 90 minutes).

## Files in this repository:

### 1. `project.ipynb` (Jupyter Notebook)
This Jupyter notebook implements the solution without using a loop. The process is as follows:
1. **Data Filtering**: Filters the dataset for movies released in the 1990s.
2. **Duration Analysis**: Visualizes the distribution of movie durations and identifies the most frequent duration.
3. **Short Action Movie Counting**: Uses vectorized operations instead of a loop to count short action movies (with a duration of less than 90 minutes).

### 2. `project.py` (Python Script)
This Python script implements the same logic but includes a `for` loop for counting short action movies. The process is as follows:
1. **Data Filtering**: Filters the dataset for movies released in the 1990s.
2. **Duration Analysis**: Visualizes the distribution of movie durations and identifies the most frequent duration.
3. **Short Action Movie Counting**: Uses a `for` loop to iterate through the data and count the number of action movies with a duration of less than 90 minutes.

## Differences Between the Notebook and Python Script:
- **project.ipynb**: Does not use a loop for counting short action movies; instead, it relies on vectorized operations for efficiency.
- **project.py**: Implements the counting of short action movies using a `for` loop, which is more manual and easier to follow for beginners.

## Requirements:
- pandas
- matplotlib

You can install the required packages by running:


