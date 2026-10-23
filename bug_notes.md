Bug Notes

1. Average Calculation Bug

- Problem: The program calculated the wrong average and caused a division-by-zero error for a single mark.
- Cause: The denominator was incorrectly written as "len(marks) - 1".
- Fix: Changed it to "len(marks)".

2. Passing Boundary Bug

- Problem: A mark of 40 was incorrectly treated as failing.
- Cause: The condition used "mark > PASS_MARK".
- Fix: Changed it to "mark >= PASS_MARK".

3. Grade Ordering Bug

- Problem: A score of 95 returned ""First"" instead of ""Distinction"".
- Cause: The "average >= 60" condition was checked before "average >= 90".
- Fix: Moved the Distinction condition before the First and Second conditions.

Final Result

All 9 unit tests pass after correcting the three bugs.