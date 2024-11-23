# GitHub Commands Cheat Sheet

A quick reference guide for common Git commands.

## Table of Contents
1. [Initializing a Repository](#initializing-a-repository)
2. [Cloning a Repository](#cloning-a-repository)
3. [Staging Changes](#staging-changes)
4. [Committing Changes](#committing-changes)
5. [Checking Repository Status](#checking-repository-status)
6. [Viewing Changes](#viewing-changes)
7. [Undoing Changes](#undoing-changes)
8. [Branching and Merging](#branching-and-merging)

---

## 1. Initializing a Repository

Initialize a new Git repository in the current directory:

```bash
git init
## 2. Cloning a Repository
Create a local copy of a remote repository:

'''bash
Copy code
git clone [url]
3. Staging Changes
Stage a specific file for commit:
bash
Copy code
git add [file]
Stage all changes in the current directory:
bash
Copy code
git add .
## 4. Committing Changes
Commit staged changes with a descriptive message:

'''bash
Copy code
git commit -m "Commit message"
## 5. Checking Repository Status
Display the current state of the working directory:

'''bash
Copy code
git status
## 6. Viewing Changes
View differences between the working directory and the last commit:
''bash
Copy code
git diff
View differences between staged changes and the last commit:
bash
Copy code
git diff --staged
## 7. Undoing Changes
Discard changes to a specific file:
bash
Copy code
git checkout -- [file]
Reset the current HEAD to the previous commit, discarding all changes:
bash
Copy code
git reset --hard HEAD
## 8. Branching and Merging
List all local branches:
bash
Copy code
git branch
