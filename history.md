# Commands used in: Git Basic Exercise #

> ## To note ##

These acts as placeholder. When you do this exercise, make sure you replace the placeholder with its respective name.

- fileName
- dirName
- branchName

## Your initial commit ##

- mkdir dirName

- cd dirName
- ls -a
- git init > ls -a
- git status
- touch fileName > ls -a > git status
- git log
- git add fileName
- git status
- git restore --staged fileName > git status
- git add fileName > git commit -m 'Commit message"
- git log > Press q

---

> ### More commits ###
>
> - nano fileName > ctrl x > y > ENTER
> - cat fileName
> - git status
> - git commit -a -m "Commit message"
> - git add fileName > nano fileName > ctrl x > y > ENTER > git commit -m "Commit message"
>
> ### Check this out ###
>
> - git log
> - Right click on second commit hash > click 'copy'
> - Press q
> - git checkout 'Second commit hash' > Enter
> - cat fileName
> - git checkout brachName
> - cat fileName

---

## Branching ##

- git branch

- git branch branchName
- git branch
- git checkout branchName > git branch > git checkout brachName > git branch
- nano fileName > ctrl x > y > Enter
- git status
- git commit -a -m "Commit message"
- git log
- git checkout branchName
- git checkout -b branchName
- git log > git branch
- type branchName > fileName[^1] [^1]:This command does not yield the desired outcomes.
- git commit -m "Commit message"
- git log
- git checkout branchName > git log
- git add fileName > nano fileName > ctrl x > y > Enter > git commit -m "Commit message"
- git checkout branchName > cat fileName
- rm fileName
- echo "text to be added" > fileName
- git commit -m "Commit message"
- git checkout branchName

---

> ### Just make sure we are still on track ###
>
> - git checkout branchName
> - ls
> - git log
> - git checkout fileName
> - ls
> - git log
> - git checkout branchName
> - ls
> - git log

---

## Merging ##

- git checkout branchName

- git merge branchName

> - ls
> - git log

- git checkout branchName

- git merge branchName
- ls > git log

> - git checkout branchName
> - git log
> - git checkout branchName
> - git log

- git push

---

## Pulling and remotes ##

- cd ../..

- git clone url
- cd dirName
- git branch > git log
- git branch -a
- git checkout -b branchName
- git remote -v

---

## Multiple Repos ##

- git log

- cd .. > cd dirName > git log
- cd > mkdir dirName
- cd dirName > git init
- touch fileName > git commit -a -m "Commit message"
- cd > cd dirName > git log

---

## gitignore ##

- touch fileName

- git status
- nano fileName > add fileName > ctrl x > y > Enter
- git status
- mkdir dirName
- cd dirName > nano fileName > ctrl x > y > Enter
- cd .. > git status
- nano fileName > add dirName > ctrl x > y > Enter
- git status
- git add fileName
- git commit -m "Commit message"
- git push

---
