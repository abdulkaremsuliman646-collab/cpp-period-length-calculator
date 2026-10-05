# C++ Period Length Calculator

A C++ console application that calculates the length of a date period in days.

The program supports calculating the period length with or without including the end date.

## Features

- Calculate the difference between two dates
- Calculate the length of a date period
- Optionally include the end date
- Handle leap years
- Handle different month lengths
- Handle month and year transitions
- Use reusable date and period structures

## Concepts Practiced

- C++ Structures
- Nested Structures
- Functions
- Const References
- Default Parameters
- Boolean Logic
- Loops
- Conditional Operators
- Date Algorithms
- Problem Solving
- Code Organization

## Date Structures

The project uses `stDate` to represent a date:

```cpp
struct stDate
{
    short Year;
    short Month;
    short Day;
};
