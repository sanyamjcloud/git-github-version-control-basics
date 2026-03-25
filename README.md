# Git and GitHub Version Control

## Overview

This repository demonstrates practical usage of Git and GitHub for version control, including repository management, branching strategies, and collaboration workflows.

## Objectives

* Understand core Git concepts
* Manage source code using version control
* Work with branches and commits
* Push and manage code on GitHub

## Tools Used

* Git
* GitHub
* Linux Terminal

## Core Concepts

* Repository initialization
* Staging and committing changes
* Branching and merging
* Remote repository management

---

## Common Workflow

### 1. Initialize Repository

```bash
git init
```

### 2. Add Files to Staging

```bash
git add .
```

### 3. Commit Changes

```bash
git commit -m "Initial commit"
```

### 4. Connect to Remote Repository

```bash
git remote add origin <repo-url>
```

### 5. Push to GitHub

```bash
git push -u origin main
```

---

## Branching Workflow

### Create a New Branch

```bash
git checkout -b feature-branch
```

### Switch Branch

```bash
git checkout main
```

### Merge Branch

```bash
git merge feature-branch
```

---

## Viewing History

```bash
git log
```

Compact view:

```bash
git log --oneline
```

---

## Project Structure

```bash
commands.txt
notes.txt
```

## How to Use

1. Clone Repository

```bash
git clone <repo-url>
cd git-github-version-control-basics
```

2. Execute commands step-by-step to understand workflow

## Sample Output

```bash
[main 1a2b3c4] Initial commit
 1 file changed, 10 insertions(+)
```

(Add screenshots of commits, branches, and GitHub repo)

## Key Concepts Covered

* Version control fundamentals
* Branching and merging strategies
* Local vs remote repositories
* Commit history tracking

## Real-World Use Cases

* Collaborative software development
* Feature-based development workflows
* Code version tracking and rollback
* CI/CD integration with GitHub

## Possible Enhancements

* Demonstrate pull requests and code reviews
* Add GitHub Actions integration
* Show conflict resolution example
* Include branching strategy (Git Flow)

## Conclusion

This repository provides a practical foundation in Git and GitHub workflows, essential for collaborative development and modern DevOps practices.
