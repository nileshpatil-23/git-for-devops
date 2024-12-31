# Git Commands Documentation

## Setting up Git

### Initialize a Git Repository
`git init`

### Configure Git User
`git config --global user.name "Your Name"`  
`git config --global user.email "your-email@example.com"`

---

## Working with Files

### View Status of Changes
`git status`

### Add Files to Staging Area
`git add <filename>`  
`git add .`

### Remove a File from Staging Area
`git rm --cached <filename>`

### Commit Changes
`git commit -m "commit message"`

---

## Branch Management

### Create a New Branch
`git checkout -b <branch-name>`

### Switch Between Branches
`git checkout <branch-name>`  
`git switch <branch-name>`

### List All Branches
`git branch`

---

## Logs and History

### View Commit Logs
`git log`

### View Simplified Commit Logs
`git log --oneline`

---

## Merging and Deleting Branches

### Merge a Branch
`git merge <branch-name>`

### Delete a Branch
`git branch -d <branch-name>`

---

## File Management

### Delete a File
`rm <filename>`

### Create a New File
`touch <filename>`

---

## Viewing and Cleaning Workspace

### List All Files (Including Hidden)
`ls -a`

### Clear Terminal
`clear`
