# Student Mark Calculator

**Name:** Adrian chiwaya.                
 **Student ID:** DCS/25/PE/014            
 **Date:** April 11, 2026

## What the program does

This program calculates a student's final mark based on their coursework and exam marks, then assigns a grade.

## How it works

1. Gets student name and ID
2. Gets coursework mark (out of 100)
3. Gets exam mark (out of 100)
4. Calculates final mark using: coursework × 50% + exam × 50%
5. Assigns grade based on final mark
6. Displays the results

## Grading scale

| Grade | Range     |
|------|-----------|
| A    | 75 - 100  |
| B    | 65 - 74   |
| C    | 50 - 64   |
| D    | 40- 49    |
| F    | 0 - 39    |

1. The student’s coursework and exam marks are collected.
2. The final mark is calculated (usually using a percentage formula).
3. The final mark is checked against the grading scale.
4. The corresponding grade is assigned automatically.

The grading scale shows how student marks are converted into grades. Each grade represents a range of scores from A (excellent) to F (fail). This helps in evaluating student performance in a simple way.

## Example

Input:
- Name: Adrian chiwaya 
- ID: DCS/25/PE/014
- Coursework: 98
- Exam: 98

Output:
- Final Mark: 98.0%
- Grade: Distinction 

## Limitations
- it doesn't keep data for records of results executed
- the system may display errors for incorrect data inputs e.g. Letters
- the grading scale is unchangeable unless the actual code itself is modified 
- it capacity is limited for one student at a time

## Assumptions
- marks entered are within specific acceptable range
- the weighting of coursework and exam is equally fixed at 50% respectively 
- the users understands to interact with the program effectively
- the user shall input data in the correct format(numbers only) 