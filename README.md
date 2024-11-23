GitHub Commands Cheat Sheet
Table of Contents
Initializing a Repository
Cloning a Repository
Staging Changes
Committing Changes
Checking Repository Status
Viewing Changes
Undoing Changes
Branching and Merging
1. Initializing a Repository
bash
Copy code
git init
Initializes a new Git repository in the current directory.
2. Cloning a Repository
bash
Copy code
git clone [url]
Creates a local copy of a remote repository.
3. Staging Changes
Stage specific files for commit:
bash
Copy code
git add [file]
Stage all changes in the current directory:
bash
Copy code
git add .
4. Committing Changes
bash
Copy code
git commit -m "Commit message"
Commits staged changes with a descriptive message.
5. Checking Repository Status
bash
Copy code
git status
Displays the current state of the working directory.
6. Viewing Changes
View differences between the working directory and the last commit:
bash
Copy code
git diff
View differences between staged changes and the last commit:
bash
Copy code
git diff --staged
7. Undoing Changes
Discard changes to a specific file:
bash
Copy code
git checkout -- [file]
Reset the current HEAD to the previous commit, discarding all changes:
bash
Copy code
git reset --hard HEAD
8. Branching and Merging
List all local branches:
bash
Copy code
git branch
Create a new branch:
bash
Copy code
git branch [branch-name]
Switch to a different branch:
bash
Copy code
git checkout [branch-name]
Merge a branch into the current branch:
bash
Copy code
git merge [branch-name]
