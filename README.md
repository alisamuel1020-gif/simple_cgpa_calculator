# CGPA Calculator

A simple, browser-based CGPA calculator supporting multiple semesters with a 5.0 scale grading system.

## Features

- **5.0 Grade Scale**: A=5.0, B=4.0, C=3.0, D=2.0, E=1.0, F=0.0
- **Multiple Semesters**: Track cumulative GPA across all academic terms
- **Real-time Updates**: CGPA recalculates instantly as you type
- **Per-Semester Stats**: See credits this semester, total credits, and CGPA

## How to Use

1. Open `cgpa-calculator.html` in any modern web browser
2. Add courses to each semester using the "+ Add Course" button
3. Enter course name, credits, and select a grade for each course
4. The CGPA updates automatically — no need to click save
5. Delete entire semesters or individual courses using the delete buttons

## Tech Stack

- Pure HTML / CSS / JavaScript (no dependencies)
- Works offline — no server required

## Example

```
Semester 1:
  Math 101 | 4 credits | A (5.0)
  Physics 100 | 3 credits | B (4.0)
  → Total: 7 credits, 5.0+3.0 = 8.0 points
  → Semester GPA: 8.0 / 7 = 1.14

Semester 2:
  Math 202 | 4 credits | A (5.0)
  Chemistry 101 | 4 credits | B (4.0)
  → Total: 8 credits, 20.0+16.0 = 36.0 points

Cumulative:
  Total credits: 15
  Total points: 44.0
  CGPA: 44.0 / 15 = 2.93
```

## License

MIT
