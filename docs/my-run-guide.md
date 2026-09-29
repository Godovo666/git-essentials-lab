# Run Guide

## Prerequisites

- JDK 17 or later (`java` and `javac` on your PATH)
- Python 3.9 or later
- A clone of this repository; no Maven, Gradle, or third-party library is needed

## Run the demo

From the repository root:

```text
python3 run.py demo
```

On Windows, use `py -3 run.py demo` if that is how you run Python 3.

## What the demo does

`run.py` compiles the Java sources in `src/library/` into a temporary directory and runs
`library.Main`. Using a fixed date (2026-09-01), the demo builds a small catalog, prints the
student and faculty borrowing limits, searches the catalog for `git`, lets the student Alex
borrow *Git Essentials*, prints the loan receipt and due date, then returns the book and
prints the return fee and the number of active loans.
