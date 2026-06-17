# Git Task - Student Submission Guide

## Objective

Clone the repository, create your own branch, complete your assigned work, and raise a Pull Request (PR).

---

## Step 1: Clone the Repository

```bash
git clone <REPOSITORY_URL>
cd <PROJECT_NAME>
```

---

## Step 2: Create Your Personal Branch

Create a branch using your full name in lowercase with hyphens.

### Example

```bash
git checkout -b karthikeyan-m
```

### Branch Naming Convention

```text
firstname-lastname
```

Examples:

```text
john-doe
priya-sharma
rahul-kumar
```

---

## Step 3: Verify Your Branch

```bash
git branch
```

Your branch should be highlighted with `*`.

Example:

```text
* karthikeyan-m
  main
```

---

## Step 4: Complete Your Task

Make the required code changes in your branch.

---

## Step 5: Stage Changes

```bash
git add .
```

---

## Step 6: Commit Changes

```bash
git commit -m "Completed assigned task"
```

---

## Step 7: Push Your Branch

```bash
git push origin <your-branch-name>
```

Example:

```bash
git push origin karthikeyan-m
```

---

## Step 8: Create Pull Request (PR)

1. Open the GitHub repository.
2. Click **Compare & Pull Request**.
3. Set:

   * **Base Branch:** `main`
   * **Compare Branch:** `<your-branch-name>`
4. Add a meaningful title.
5. Add a short description of your changes.
6. Click **Create Pull Request**.

---

## Pull Request Format

### Title

```text
[Student Task] Your Name
```

Example:

```text
[Student Task] Karthikeyan M
```

### Description

```text
Name: Karthikeyan M

Changes Made:
- Added feature X
- Updated module Y
- Fixed issue Z
```

---

## Important Rules

* Do NOT commit directly to the `main` branch.
* Do NOT create multiple branches.
* Use only your personal branch.
* Ensure your code builds successfully before pushing.
* Raise only one PR unless instructed otherwise.
* Resolve merge conflicts before requesting review.

---

## Submission Checklist

* [ ] Repository cloned
* [ ] Personal branch created
* [ ] Task completed
* [ ] Changes committed
* [ ] Branch pushed to GitHub
* [ ] Pull Request created
* [ ] PR title and description added correctly

---

## Useful Commands

```bash
git clone <REPOSITORY_URL>

git checkout -b <your-branch-name>

git status

git add .

git commit -m "Completed assigned task"

git push origin <your-branch-name>
```

Happy Coding 🚀
