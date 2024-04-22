# Date Operations C++ Program

This C++ program demonstrates basic date operations such as date validation, day of the week calculation, and finding the difference between two dates. It includes a `Date` struct with member functions to perform these operations.

## Table of Contents

1. [Dependencies](#dependencies)
2. [File Structure](#file-structure)
3. [Code Explanation](#code-explanation)
4. [License](#license)

## Dependencies

- C++ compiler (supporting at least C++11 standard)
- Standard C++ library

## File Structure

- `main.cpp`: The main C++ source code file containing the `Date` struct definition and the `main()` function.
- `README.md`: This file, providing an overview of the program and its usage.


5. Follow the prompts to input a date, and the program will display whether the date is valid, the day of the week, and the difference between two dates.

## Code Explanation

The `main.cpp` file contains the following components:

- Definition of the `Date` struct, which holds information about a date and includes member functions for date validation, day of the week calculation, and finding the difference between dates.
- `isValid()` function: Checks if a date is valid by verifying the month range and considering leap years for February.
- `dayOfWeek()` function: Calculates the day of the week for a given date using Zeller's Congruence algorithm.
- `difference()` function: Computes the difference in days between two dates.
- `main()` function: The entry point of the program where date input, validation, and operations are performed. It also displays the results to the user.
