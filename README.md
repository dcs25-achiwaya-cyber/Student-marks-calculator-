# Student Mark Calculator

**Name:** Adrian chiwaya.                
 **Student ID:** DCS/25/PE/014            
 **Date:** April 11, 2026

## What the program does

This program is used to calculate a student’s final mark using coursework and exam scores. It takes the two inputs, combines them equally, and produces one final result.

After getting the final mark, the program checks it against a grading scale to assign a grade. The final output shows the student’s name, ID, mark, and grade in an easy-to-understand format.

## How it works

1. First, the program collects the student’s name and ID.
2. Then it takes coursework and exam marks as input.
3. It computes the final score using equal weighting (50/50).
4. The result is compared with the grading scale.
5. A grade is assigned based on the final mark.
6. The student’s details, mark, and grade are displayed.

## Grading scale

| Grade | Range              |
|------|-------------------|
| Distinction   | 75 - 100 |
| Credit        | 65 - 74  |
| Pass          | 50 - 64  | 
| Fail          | 0 - 49   |

1. The program receives student's coursework and exam marks as input. 
2. The final mark is calculated (usually using a percentage formula).
3. The final mark is checked against the grading scale.
4. The corresponding grade is assigned automatically.

The grading scale shows how student marks are converted into grades. Each grade represents a range of scores from Distinction (highest) to Fail (lowest). This helps in evaluating student performance in a simple way.

## Example

Input:
- Name: Adrian chiwaya 
- ID: DCS/25/PE/014
- Coursework: 98
- Exam: 98

Output:
- Final Mark: 98%
- Grade: Distinction

## Limitations
- It does not keep data for records of results executed
- The system may display errors for incorrect data inputs e.g. Letters
- The grading scale is unchangeable unless the actual code itself is modified 
- Its capacity is limited for one student at a time

## Assumptions
- Marks entered are within specific acceptable range
- The weighting of coursework and exam is equally fixed at 50% respectively 
- The user understands to interact with the program effectively
- The user shall input data in the correct format numbers only (marks must be numeric) 