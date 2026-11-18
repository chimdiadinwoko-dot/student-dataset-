# student-dataset-
Nwoko Sullivan 24/14002
A Python script that generates a fictional dataset of 200 students.

## Columns
| Column | Description |
|---|---|
| Student ID | Unique ID (e.g. STU0001) |
| Department | Cybersecurity, Computer Science, Software Engineering, Information Technology, Data Science |
| Level | 100, 200, 300 or 400 |
| Attendance Percentage | 40 - 100 |
| Average Examination Score | 20 - 100 (loosely tied to attendance) |

## How to run
```bash
python generate_dataset.py
```
This creates `student_dataset.csv`. No external libraries needed (Python 3.8+).

## Notes
All data is fictional and randomly generated. A fixed random seed (42) makes the output reproducible.
