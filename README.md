# Assignment 1: Clean Code Refactoring
Problem

A single function calculates salary, deductions, and bonus using unclear variables and long logic.
def cal(a, b, c):
    t = a * b
    if t > 50000:
        d = t * 0.1
    else:
        d = t * 0.05
    if c > 5:
        bn = 5000
    else:
        bn = 2000
    return t - d + bn

## Objective
Refactor the given codebase to improve readability, maintainability,
and adherence to clean code principles.

## Tasks
1. Analyze the code in `src/original/`
2. Identify:
   - Long methods
   - Poor naming
   - Duplicate code
   - Magic numbers
3. Refactor the code into `src/refactored/` by applying:
   - Single Responsibility Principle
   - Meaningful naming
   - Modular design
4. Ensure functionality remains unchanged.

## Deliverables
- Refactored source code
- `analysis.md` explaining applied clean code principles
- `report.md` comparing before vs after

## Submission Instructions
Commit all changes and push to your assigned repository.

