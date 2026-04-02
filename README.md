# Task 1: Git Basics and Branching

## Objective

Learn the fundamentals of Git including initialization, basic commits, and working with branches:

- Initialize a Git repository
- Understand the basic Git workflow
- Create and switch between branches
- Merge branches and resolve conflicts
- Understand HEAD, master, and branch pointers

## Setup Instructions

This task is part of the git-fundamentals project. Ensure you have:

- Git installed on your system
- A code editor (VS Code recommended)
- Basic understanding of command line/terminal
- Familiarity with HTML, CSS, and JavaScript

## Exercise Overview

This task covers the fundamental concepts of Git that are essential for version control:

### 1. Repository Initialization

**Command:**

```bash
git init
```

- Creates a new `.git` directory in your project
- Initializes version control tracking
- Sets up the default branch (usually `master` or `main`)

### 2. Basic Git Workflow

The typical Git workflow involves three stages:

1. **Working Directory** - Where you edit files
2. **Staging Area (Index)** - Where you prepare changes for commit
3. **Repository (.git)** - Where commits are permanently stored

### 3. Creating Commits

```bash
git add <file>
git commit -m "descriptive message"
```

- `git add` stages changes
- `git commit` creates a snapshot of staged changes

### 4. Branching

**Create a new branch:**

```bash
git branch branch-name
git checkout branch-name
```

**Or create and switch in one command:**

```bash
git checkout -b branch-name
```

**List all branches:**

```bash
git branch -a
```

### 5. Merging Branches

```bash
git checkout master
git merge branch-name
```

- Combines changes from one branch into another
- May result in merge conflicts if both branches modified the same lines

## Key Concepts

- **Repository**: A `.git` directory that stores all version control information
- **Branch**: A pointer to a specific commit; allows parallel development
- **HEAD**: Reference to the current branch and commit
- **Commit**: A permanent record of changes with a unique hash
- **Staging Area**: Intermediate layer between working directory and repository
