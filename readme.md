Bug Fixing Using AI

Project Overview

This project demonstrates how Python bugs can be identified and corrected using unit testing and AI-assisted debugging.

Files

- "student_utils.py" — Contains functions to calculate average marks, check passing status, and assign grades.
- "test_student_utils.py" — Contains nine unit tests to verify the functions.
- "bug_notes.md" — Documents the bugs, their causes, and their fixes.

Bugs Fixed

1. Average calculation: Corrected the denominator to "len(marks)".
2. Passing boundary: Changed ">" to ">=" so a mark of 40 counts as passing.
3. Grade ordering: Checked Distinction before First and Second.

How to Run the Tests

Make sure Python is installed, open a terminal in the project folder, and run:

python test_student_utils.py

Test Results

- Total tests: 9
- Status: All 9 tests passed.

RED → FIX → GREEN

- RED: The original buggy implementation failed the tests.
- FIX: Corrected the average calculation, passing boundary, and grade ordering.
- GREEN: Reran the same nine tests; all passed.

Tools Used

- Python
- "unittest"
- Google Colab
- AI-assisted debugging
- Cursor