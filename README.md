# C_assignment2: Data Processing and Analysis in C

## Overview
This project is part of the COMP20005 Introduction to Numerical Computation course. The goal is to implement a generic program in C capable of reading and processing CSV files containing numerical data, while performing various data analysis tasks such as computing averages, generating graphs, and performing statistical calculations.

## Features
- Use of arrays of structs in C.
- Apply engineering processes for assembling and testing a non-trivial program.
- Process and manipulate datasets stored in CSV format.

## Background
The program will handle CSV files with numerical data, where the first line contains column headers and subsequent lines contain numerical values. The task involves developing commands that compute averages, generate graphs, and perform correlation analysis.

## Task Stages

### Stage 1 – Column Averages (8/20)
Implement a command to compute the average, max, and min of the values in a specified column. Output should be formatted to two decimal places.

### Stage 2 – Graphing Distributions (16/20)
Develop a command to generate a histogram-like graph of values in a specified column, divided into 20 equal regions. The graph should be scaled using a factor to ensure no row exceeds 50 stars.

### Stage 3 – More Functionality (20/20)
1. **Category Averages (Command `c`)**: Compute averages of a column based on categories defined in another column.
2. **Kendall's Tau Correlation (Command `k`)**: Calculate the Kendall’s tau correlation coefficient between two columns.

## Commands
- `i`: List column names.
- `d`: Dump entire CSV data.
- `a <column>`: Calculate average for a specific column.
- `g <column>`: Generate a graph for the specified column.
- `c <category_column> <value_column>`: Compute category averages.
- `k <column1> <column2>`: Compute Kendall’s tau correlation between two columns.

## Compilation and Usage
1. Compile the program using:
   ```bash
   gcc -o data_processor main.c functions.c
2. Run the program:
  ```bash
  ./data_processor <csv_file>
  ```
3. Enter commands as prompted.

## Technologies  
- C  

## Contributors
- Ryan Huang
- University of Melbourne COMP20005 Teaching Team (Question Provider)

## License
This project is for academic purposes under the University of Melbourne's COMP20005 course.

