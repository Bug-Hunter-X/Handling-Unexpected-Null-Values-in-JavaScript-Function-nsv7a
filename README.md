# Handling Unexpected Null Values in JavaScript

This repository demonstrates a common JavaScript bug related to unexpected null values and its solution.

## Bug Description

The original code lacked explicit handling of null values passed as arguments. This could result in errors, particularly if the function performs calculations or operations that are undefined for null values.

## Solution

The solution introduces explicit null checks at the beginning of the function. If either argument is null, the function immediately returns null, preventing subsequent operations on null values and avoiding potential errors.

## How to reproduce the bug

Run the original code (in `bug.js`) passing in null values. Observe any errors or unexpected results.

## How to run the solution

Run the improved code (in `bugSolution.js`) and observe its improved error-handling.

This example highlights the importance of defensive programming in JavaScript to avoid unexpected errors and improve the robustness of your code.