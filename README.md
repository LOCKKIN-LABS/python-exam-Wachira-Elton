[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/e5kWAqyL)
[![Work in MakeCode](https://classroom.github.com/assets/work-in-make-code-8824cc13a1a3f34ffcd245c82f0ae96fdae6b7d554b6539aec3a03a70825519c.svg)](https://classroom.github.com/online_ide?assignment_repo_id=24003547&assignment_repo_type=AssignmentRepo)

# Python Exam: FizzBuzz & Workflow Management

## Part 1: The Git Protocol (Strictly Enforced)
You are working on a production codebase. You must execute the following workflow exactly:

1. Clone this repository locally.
2. Create a branch named `feature/fizzbuzz-logic`. Switch to it.
3. Inside `feature/fizzbuzz-logic`, implement the FizzBuzz rules below *inside the marked section*. Do not alter the input lines. Commit and push this branch.
4. Go back to `main`. You will notice a bug: the terminal input uses `float(input())` instead of `int(input())`. 
5. Create a branch named `hotfix/input-validation` off `main`. Fix the float bug to be an integer. Commit and push this branch.
6. Merge `hotfix/input-validation` directly into `main` on GitHub.
7. Open a Pull Request on GitHub to merge `feature/fizzbuzz-logic` into `main`. 
8. **Crucial:** You will hit a Merge Conflict because both tasks modified `solution.py`. Resolve the conflict natively, finalize the merge, and ensure your final working code is on `main`.

## Part 2: The Core Logic
Write the Python logic inside `solution.py`:
- Divisible by 3 -> print "Alpha"
- Divisible by 5 -> print "Beta"
- Divisible by both 3 and 5 -> print "AlphaBeta"
- Otherwise -> print the integer number itself.
