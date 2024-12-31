# Git Commands Documentation

Setting up Git

1.Initialize a Git Repository
    git init

2.Configure Git User
    git config --global user.name "Your Name"
    git config --global user.email "your-email@example.com"

3.Working with Files
    View Status of Changes
    git status

4.Add Files to Staging Area
    git add <filename>
    git add .

5.Remove a File from Staging Area
    git rm --cached <filename>

6.Commit Changes
    git commit -m "commit message"

7.Branch Management
    Create a New Branch
    git checkout -b <branch-name>

8.Switch Between Branches
    git checkout <branch-name>
    git switch <branch-name>

9.List All Branches
    git branch

10.Logs and History
    View Commit Logs
    git log

11.View Simplified Commit Logs
    git log --oneline

12.Merging and Deleting Branches
    Merge a Branch
    git merge <branch-name>

13.Delete a Branch
    git branch -d <branch-name>

14.File Management
    Delete a File
    rm <filename>

15.Create a New File
    touch <filename>

16.Viewing and Cleaning Workspace
    List All Files (Including Hidden)
    ls -a

17.Clear Terminal
    clear
