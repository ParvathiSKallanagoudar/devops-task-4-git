# Git Workflow Documentation

## Branches
- main: stable and reviewed changes.
- dev: integration branch for ongoing development.
- feature: branch used to develop an individual change.

## Standard Workflow
1. Create a feature branch from dev.
2. Make changes and review them.
3. Stage and commit the changes.
4. Push the feature branch to GitHub.
5. Open a pull request from feature to dev.
6. Merge the pull request after review.
7. Open a pull request from dev to main.
8. Merge the reviewed changes into main.

## Useful Git Commands
- git status: inspect working-tree changes.
- git branch: list branches.
- git switch: change branches.
- git add: stage changes.
- git commit: save a snapshot.
- git log: inspect commit history.
- git merge: integrate branch changes.
- git stash: temporarily store uncommitted changes.
- git tag: mark a version.
- git push: upload commits to a remote repository.
