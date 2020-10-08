# Git and Github


## Learning Goals

* Explain the difference between remote and local repositories
* Create a Git repository locally
* Create a repository on GitHub
* Link a local repository to a remote repository
* Use a branching workflow with Git and GitHub









# Warmup

Take a minute and jot down:
  - what you already know about Git/Github.
  - why do we use Git/Github?







## Overview

* Git is a
 version control system that we use in programming.

* GitHub is a website that allows us to share Git repositories.

* In order to keep our code safe we use a branching workflow that allows us to make changes to multiple files before fully committing to those changes.



## Commits
- Unstaged
- Staged
- Committed












### Important Git Commands

* git init - initialize a local git repository

* git symbolic-ref HEAD refs/heads/main (to switch the default of master to main)
**Do this at the beginning of your project**

* git commit -m "message describing functionality"

* git remote -v

* git checkout -b <name_of_branch>




## Git Workflow  

1. Update our local repository
  - `git pull origin main`
2. Create new branch to work on
  - `git checkout -b <name_of_branch>`
3. Do work
  - git add <file_name>
  - git commit
  - repeat as needed until work on branch is completed
4. Push local branch to remote repository
  - `git push origin <branch_name>`
5. Go to github (remote repository) and make a Pull Request (PRs)
6. Go back to machine and go back to main
  - `git checkout main`
7. Updates local main with the changes from remote repo
  - 'git pull origin main'




Overview Quick Sheet
1. Update local main
2. Make a new branch
3. Add work to the branch
4. Push branch up to remote repo
5. Create a Pull Request on GitHub
6. Merge PR on GitHub
7. On local, switch to main branch
* Repeat
