#programming 

**What is git?

Git is used to track changes on a project between multiple versions and people.

**How to use?

We can use it from the terminal. cd into your project. I am assuming that [[GitHub]] and gitlab are some kind of online-variant, way to use git. I want to learn about them next.

**Vocabulary**

*Repository:* a project that uses git to control versions
*Branch*: allows you to branch off on an older or current version of the repo, aside from the main

**Commands:**

Configure name & email: 
- git config --global user.name "Collin DeSantis"
- git config --global user.email "collindesantis@gmail.com"

Create a repository:
- git init (cd inside project)

Show status of the repo:
- git status (will show changes to be committed & untracked files)

Stage a commit: (save changes but do not commit them yet, so we can commit different things at different times if we are not finished)
- git add item

Commit all staged items:
- git commit -m "commit message"

Show commit log:
- git log

Return to a previous state of the project:
- git checkout *commit-hash* (get hash from log) **or** branch-name

List branches:
- git branch

Create new branch:
- git branch *name*

Merge 2 branches:
- git merge branch-name (merges to master)

Stash code (will save it for later and give you a clean directory):
- git stash -u