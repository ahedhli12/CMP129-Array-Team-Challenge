# CMP 129 – Array Team Challenge

## Team Programming Project

### Goal

Work as a programming team to analyze an array of student exam scores.

Your team will practice:

- Traversing arrays with loops
- Using `.length`
- Performing calculations with array values
- Finding the highest value
- Using conditions with arrays
- Searching an array
- Testing and debugging Java programs
- Explaining programming logic
- Collaborating with classmates in Visual Studio Code

---

## Team Setup

Work in teams of **2–3 students**.

You will work together on **one program**.

Use **Visual Studio Code Live Share** so everyone can participate in the programming process.

### Team Roles

For each challenge, assign the following roles.

**Programmer / Driver**
- Types the code.
- Runs the program.
- Explains what they are writing.

**Problem Solver / Navigator**
- Helps determine the logic.
- Watches the code as it is written.
- Suggests the next step.
- Checks loop conditions and array indexes.

**Tester / Reviewer**
- Tests the program.
- Checks the output.
- Looks for errors.
- Asks the programmer to explain the code.

### Rotate Roles

After completing each challenge, **rotate roles**.

Everyone should have an opportunity to participate in writing, explaining, and testing the program.

If your team has only two students, share the Tester/Reviewer responsibilities.

---

# Starting Data

Your program will use:

```java
int[] scores = {78, 92, 85, 67, 95, 88, 73, 90};
```

Do not change the starting array until your team has completed and tested the required challenges.

---

# Challenge 1 – Display the Scores

Use a loop to display every score in the array.

Do not write a separate `println()` statement for every value.

Expected output:

```text
78
92
85
67
95
88
73
90
```

### Team Check

Before moving on, make sure everyone can explain:

- What does `scores.length` represent?
- Why does the loop start at index `0`?
- What does `scores[i]` mean?

**Rotate team roles before Challenge 2.**

---

# Challenge 2 – Calculate the Average

Calculate and display the average of all scores.

Expected output:

```text
Average Score: 83.5
```

Requirements:

- Use a loop.
- Do not manually add the scores.
- Use `scores.length` when calculating the average.
- Your program should continue working if additional scores are added to the array.

### Team Check

Explain:

- How was the total calculated?
- Why should `scores.length` be used instead of the number `8`?
- Why might the average need to use a `double`?

**Rotate team roles before Challenge 3.**

---

# Challenge 3 – Find the Highest Score

Use a loop to determine the highest score in the array.

Expected output:

```text
Highest Score: 95
```

Requirements:

- Do not simply print `95`.
- Your program must determine the highest value from the array.
- Your solution should continue working if the values in the array change.

### Team Check

Discuss:

- What should the starting value of the `highest` variable be?
- Why do we compare each array value with the current highest value?

**Rotate team roles before Challenge 4.**

---

# Challenge 4 – Scores Above Average

Determine how many scores are greater than the calculated average.

Expected output:

```text
Students Above Average: 5
```

Requirements:

- Use the average calculated in Challenge 2.
- Use a loop and an `if` statement.
- Do not hard-code the answer.

### Team Check

Your team should be able to identify which scores are above the average.

---

# Team Testing Challenge

Before moving to the bonus challenges, change the array temporarily to:

```java
int[] scores = {70, 80, 90, 100};
```

Predict the following **before running the program**:

- Average
- Highest score
- Number of scores above average

Run your program and compare the results with your prediction.

Then restore the original array.

This test demonstrates that your program works with different data and that the answers were not hard-coded.

---

# Bonus Challenge 1 – Reverse Order

Display all scores in reverse order.

Expected output:

```text
90
73
88
95
67
85
92
78
```

Do not create another array.

Think about:

- What index should the loop start at?
- What index should the loop stop at?
- Should the loop counter increase or decrease?

---

# Bonus Challenge 2 – Score Search

Ask the user to enter a score.

Your program should:

1. Search the array for the entered score.
2. Display whether the score was found.
3. Display the index of the **first occurrence**.
4. Display how many times the score appears.
5. Display an appropriate message if the score does not appear.

Example:

```text
Enter a score to search for: 92

Score found.
First index: 1
Number of occurrences: 1
```

Remember that Java array indexes begin at `0`.

Do not hard-code the result.

---

# Bonus Challenge 3 – Lowest Score

If your team finishes early, determine the **lowest score** in the array.

Example:

```text
Lowest Score: 67
```

Your solution should continue working if the array values change.

---

# Bonus Challenge 4 – Sort and Analyze

If your team finishes all previous challenges, sort the scores from lowest to highest.

You may research the Java `Arrays.sort()` method.

Expected result:

```text
67 73 78 85 88 90 92 95
```

Discuss with your team:

**Was sorting necessary to calculate the average, highest score, or scores above average?**

Be prepared to explain why or why not.

---

# GitHub Copilot

First, work with your team and attempt each problem yourselves.

If your team becomes stuck, you may use GitHub Copilot for:

- A small hint
- An explanation
- Help understanding an error
- Debugging assistance

Example prompt:

> I am learning Java arrays. Give me a hint for finding the largest value in an integer array. Do not write the complete solution.

Do **not** ask Copilot to complete the entire activity.

Record any Copilot assistance in `AI-Use-Report.md`.

Your team is responsible for understanding all code in the final program.

---

# Team Completion Check

Before your team finishes, every member should be able to answer the following questions:

1. What is an array?
2. What does `scores.length` return?
3. Why do Java array indexes begin with `0`?
4. How did your team calculate the average?
5. How did your team determine the highest score?
6. How did your team count scores above the average?
7. How would you search an array for a specific value?
8. What part of the program did you personally help develop?
9. What error or problem did your team encounter, and how did you solve it?

---

# Team Submission

Your team should submit:

- Completed `ArrayTeamChallenge.java`
- Completed `AI-Use-Report.md`
- Working program with all four required challenges
- Any completed bonus challenges

### Important

This is a **team programming activity**, not three separate individual problems.

Discuss the solution together, rotate roles, test each other's work, and make sure **every team member understands the final program**.
