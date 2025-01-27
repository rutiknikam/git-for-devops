# Git Commands Guide

## 1. Creating a New Repository
- **Create a new directory**:  
  `mkdir git-for-devops`
- **Navigate to the directory**:  
  `cd git-for-devops/`
- **Initialize Git repository**:  
  `git init`

---

## 2. Viewing Files and Directory Information
- **List files in the directory**:  
  `ls`
- **Show the current directory path**:  
  `pwd`

---

## 3. Working with Files
- **Create or edit a file**:  
  `vim <filename>`
- **View file content**:  
  `cat <filename>`
- **Create multiple files**:  
  `touch file1.txt file2.txt`
- **Remove a file**:  
  `rm <filename>`

---

## 4. Tracking Changes
- **Check the repository status**:  
  `git status`
- **Add specific files to staging area**:  
  `git add <filename>`
- **Add all changes to staging area**:  
  `git add -a` or `git add --all`
- **Commit changes**:  
  `git commit -m "commit message"`

---

## 5. Configuring User Information
- **Set global username**:  
  `git config --global user.name "<username>"`
- **Set global email**:  
  `git config --global user.email "<email>"`

---

## 6. Branch Management
- **List all branches**:  
  `git branch`
- **Create and switch to a new branch**:  
  `git checkout -b <branch-name>`
- **Switch to an existing branch**:  
  `git checkout <branch-name>`

---

## 7. Viewing Logs and History
- **View commit history**:  
  `git log`
- **View commit history in one line**:  
  `git log --oneline`
- **View command history**:  
  `history`

---

## 8. Restoring and Removing Files
- **Restore a deleted file**:  
  `git restore <filename>`
- **Remove a file from the working directory**:  
  `rm <filename>`

---

## 9. Clearing Terminal
- **Clear the terminal screen**:  
  `clear`

---

## 10. Updating and Committing Changes
- **Commit changes with a message**:  
  `git commit -m "commit message"`
- **Stage all changes and commit in one step**:  
  `git add -a`  
  `git commit -m "commit message"`
