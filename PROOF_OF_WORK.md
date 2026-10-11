
# DevOps Class Activity - Proof of Work

**Student Name:** Malik Hamza Shahid
**SAP ID:** 54523
**Repository:** https://github.com/Hamza54523/devops-git-challenge

## Git Commit History

Command used:
git log --oneline

Output:

b67375d Merge pull request #1 from Hamza54523/development
3ca18d5 fix: resolved merge conflict
e2d2053 fix: staging label
f25d8ba feat: updated script with staging env
efae618 feat: initial commit with deploy script
6140589 Initial commit

## Reflection Questions

### Q1: What is the difference between Git and GitHub?

Git is a version control tool that tracks changes in our project files. It works locally on our computer and helps us manage different versions of code. GitHub is an online platform where we can store Git repositories and share our work with others. It also allows developers to collaborate through Pull Requests.

### Q2: Explain the three Git architecture stages: Working Directory, Staging Area, and Local Repository.

The Working Directory is where we create and edit our project files. The Staging Area is where we select changes that we want to include in the next commit using git add. The Local Repository stores committed changes and maintains the project's history. These three stages help us organize and track our work.

### Q3: What is the difference between git stash pop and git stash apply?

Both commands restore changes that were temporarily saved using git stash. The git stash pop command restores the changes and removes the stash entry if it is applied successfully. The git stash apply command restores the changes but keeps the stash entry saved. We use apply when we may need the same saved changes again.

### Q4: What is the difference between git fetch and git pull?

The git fetch command downloads the latest changes from a remote repository without merging them into our current branch. It allows us to review the changes before applying them. The git pull command downloads the changes and then integrates them into our current branch. We use pull when we want to update our local branch with remote changes.
