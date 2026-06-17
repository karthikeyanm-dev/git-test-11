# Git Task - Fork, Clone, Branch, Code & Pull Request

## Objective

Complete the Git workflow by forking the repository, creating your own branch, adding a Java program, and raising a Pull Request.

---

## Step 1: Fork the Repository

1. Open the repository link provided by the instructor.
2. Click the **Fork** button in the top-right corner.
3. This will create a copy of the repository under your GitHub account.

---

## Step 2: Clone Your Fork

```bash
git clone https://github.com/<your-github-username>/<repository-name>.git
```

Navigate into the project directory:

```bash
cd <repository-name>
```

---

## Step 3: Create Your Branch

Create a branch using your name.

Example:

```bash
git checkout -b karthikeyan
```

Verify the branch:

```bash
git branch
```

---

## Step 4: Create Java Program

Create a file named:

```text
LargestOfThreeNumbers.java
```

Add the following Java program:

```java
public class LargestOfThreeNumbers {

    public static void main(String[] args) {

        int a = 10;
        int b = 25;
        int c = 15;

       // Logic Goes Here
    }
}
```

---

## Step 5: Commit Your Changes

Check status:

```bash
git status
```

Add files:

```bash
git add .
```

Commit changes:

```bash
git commit -m "Added program to find largest of three numbers"
```

---

## Step 6: Push Your Branch

```bash
git push origin <your-branch-name>
```

Example:

```bash
git push origin karthikeyan
```

---

## Step 7: Create a Pull Request

1. Open your forked repository on GitHub.
2. Click **Compare & Pull Request**.
3. Ensure:

   * Source Branch = Your Branch
   * Target Branch = main
4. Add a meaningful title and description.
5. Click **Create Pull Request**.

---

## Submission Checklist

* [ ] Repository Forked
* [ ] Repository Cloned
* [ ] Branch Created Using Your Name
* [ ] Java Program Added
* [ ] Changes Committed
* [ ] Branch Pushed
* [ ] Pull Request Raised

---

## Branch Naming Convention

Use only your name in lowercase.

Examples:

```text
karthikeyan
arun
priya
rahul
```

---

## Pull Request Title Format

```text
Added Largest Of Three Numbers Program - <Your Name>
```

Example:

```text
Added Largest Of Three Numbers Program - Karthikeyan
```
