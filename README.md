# JAVA-Learning
This repository contains all the Learnings in Java professional programming.


# Clean Code Book Learnings
- Prefer a small function over if-else:
```
  if (cell[STATUS_VALUE] == FLAGGED)
    flaggedCells.add(cell);
```
- Preferred way:
  ```
  if (cell.isFlagged())
    flaggedCells.add(cell);
  ```
