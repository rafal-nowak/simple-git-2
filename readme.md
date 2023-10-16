Git
=================

Fundamental Git commands:
- ```git init```: Initialize a new Git repository.
- git clone: Clone an existing Git repository.
- git add: Stage changes for commit.
- git commit: Commit changes with a message.
- git status: Check the status of your working directory.
- git log: View commit history.
- git branch <branch_name>: create branch.
- git checkout <commit_hash>: switch between branches / commits.
- git reset --hard <commit_hash>: move your current branch to a different commit in the history.

Merging a Feature Branch into main:
Ensure you're on the main branch:
- git checkout main

Merge the feature branch into main:
- git merge feature-branch

Delete the local branch: 
- git branch -d <branch_name>

List all remote branches: 
- git branch -r

Delete the remote branch: 
- git push origin --delete <branch_name>