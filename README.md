# GIT Practice

It is a GIT Practice

## Bash

```bash
git init
git add .
git commit -m "Commit with version 1.0.0"
git tag "v1.0.0"
git branch -M master
git branch feature1
git checkout feature1
git add .
git commit -m "Adding Feature 1"
git checkout master
git merge feature1
git tag "v1.0.1"
git branch hotfix
git branch feature2
git checkout hotfix
git add .
git commit -m "Feature 1 fixed"
git checkout master
git merge hotfix
git tag "v1.1.0"
git checkout feature2
git add .
git commit -m "Adding Feature 2"
git checkout master
git merge feature2
git add .
git commit -m "Conflict merges resolve bettween feature and master"
git tag "v1.2.0"
```
