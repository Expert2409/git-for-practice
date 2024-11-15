# Git Commands

This document provides an overview of commonly used Git commands and their descriptions.

## Initializing a Git Repository

- `git init`  
  Initializes a new Git repository in the current directory.

## Checking Repository Status

- `git status`  
  Shows the current status of the working directory and staging area. It lists untracked files, changes that are staged for commit, and changes that are not yet staged.

## Viewing File Changes

- `git diff`  
  Shows the differences between the working directory and the staging area. This helps you see what changes have been made since the last commit.

## Adding Files to Staging Area

- `git add <file>`  
  Stages a specific file, preparing it to be committed.
  
- `git add .`  
  Stages all modified and new files in the directory for commit.

## Committing Changes

- `git commit -m "commit message"`  
  Commits the changes in the staging area with a message describing the changes.

## Viewing Commit History

- `git log`  
  Displays a detailed history of commits in the current branch.

- `git log --oneline`  
  Shows a simplified, one-line view of the commit history.

## Managing Branches

- `git branch`  
  Lists all the branches in the repository and indicates the current branch.

- `git checkout <branch>`  
  Switches to a specified branch.

- `git checkout -b <branch>`  
  Creates a new branch and switches to it.

- `git merge <branch>`  
  Merges changes from the specified branch into the current branch.

## Removing Files

- `git rm <file>`  
  Removes a file from the working directory and stages it for commit.

- `git rm --cached <file>`  
  Removes a file from the staging area, but leaves it in the wo
