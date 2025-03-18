# Git Practice Repository

This repository is a hands-on practice space for learning and mastering Git commands and workflows. It includes examples of creating repositories, branching, committing, pushing, pulling, merging, and working with pull requests.

---


## Description

This repository serves as a learning tool for understanding version control using Git. It includes examples and exercises for common Git commands and workflows, such as:

- Creating and cloning repositories.
- Branching, committing, and reverting changes.
- Pushing and pulling changes.
- Merging branches and resolving conflicts.
- Creating and reviewing pull requests.

---

## Git Commands Practiced

### 1. **Setup and Configuration**
- `git config --global user.name "Mahmud"`  
  _Set global username_
- `git config --global user.email "mahmudghali01@gmail.com"`  
  _Set global email_

### 2. **Repository Management**
- `git init`  
  _Initialize a new Git repository_
- `git clone <https://github.com/Haleem001/git-practice.git>`  
  _Clone a remote repository_
- `git remote add origin <https://github.com/Haleem001/git-practice.git>`  
  _Link local repo to remote_

### 3. **Branching and Switching**
- `git branch`  
  _List branches_
- `git branch feature-branch`  
  _Create a new branch_
- `git checkout feature-branch`  
  _Switch to a branch_
- `git switch feature-branch`  
  _(Alternative to checkout for switching branches)_
- `git branch -m feature-branch`  
  _Rename the current branch_

### 4. **Making Changes and Committing**
- `git add .`  
  _Stage all files_
- `git commit -m "initial commit"`  
  _Commit staged changes_
- `git commit --amend -m "second commit"`  
  _Modify last commit_

### 5. **Pushing and Pulling**
- `git push origin main`  
  _Push changes to remote_
- `git pull origin main`  
  _Pull latest changes from remote_
- `git fetch origin`  
  _Fetch remote changes without merging_

### 6. **Merging and Conflicts**
- `git merge feature-branch`  
  _Merge branch into current branch_
- `git mergetool`  
  _Resolve conflicts using a merge tool_

### 7. **Undoing Changes**
- `git reset --soft HEAD~1`  
  _Undo last commit but keep changes_
- `git reset --hard HEAD~1`  
  _Undo last commit and discard changes_
- `git revert <commit_hash>`  
  _Revert a specific commit_

### 8. **Pull Requests (GitHub)**
1. Push branch to remote:  
   `git push origin <branch>`
2. Open a pull request on GitHub
3. Review and merge the pull request

### 9. **Viewing History**
- `git log --oneline`  
  _View commit history_
- `git status`  
  _Check status of working directory_
- `git diff`  
  _Show changes between commits_
