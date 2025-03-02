# My DevOps Journey 🚀

## Introduction🌟
Hello I am Shara Rahman.
Welcome to my DevOps learning notes! This file contains all the concepts, tools, and practices I've explored as a beginner in DevOps.

---
## 📘 Contents
-  [What is DevOps?](#what-is-devops)
-  [Courses and Certifications](courses_and_certifications)
-  [Commands Covered](#command_covered)
-  [Topics Covered](#topics_covered)
-  [Ultimate System Desgin Guide](https://medium.com/@shivambhadani_/system-design-for-beginners-everything-you-need-in-one-article-c74eb702540b)
-  [Deploy a Static Website in EC2 Successfully](Deploy_a_Static_Website_in_EC2_Successfully)
-  [Deploying a Todo App to AWS EC2](Deploying_a_Todo_App_to_AWS_EC2)
-  [CI/CD Pipeline](CI/CD_Pipeline)
---
## 💻 What is DevOps?
DevOps is a set of practices that combines software development (Dev) and IT operations. DevOps aims to deliver products that are ready for release at any time. 

---
## Tools and Technologies 🛠️
Here’s a list of essential DevOps tools and platforms:
- **Version Control**: [Git](https://git-scm.com), [GitHub](https://github.com)
- **CI/CD**: [GitLab CI/CD](https://docs.gitlab.com/ee/ci/)
- **Containerization**: [Docker](https://www.docker.com)
- **Cloud Platforms**: [AWS](https://aws.amazon.com)

---
## **🏆 Courses and Certifications**
- [Git Mastery: Beginner to Expert with GitHub & GitLab](https://www.udemy.com)
- [100 Days of Code: The Complete Python Pro Bootcamp](https://www.udemy.com)

---
## **🤖 Commands Covered**

### **Set your username and email (global configuration)**
- `git config --global user.name "Your Name"` - Set user name.
- `git config --global user.email "your-email@example.com"` - Set user email.
- `git config --list` -To check if everything is set up correctly.

### **Repository Management**
- `git init` - Initialize a new Git repository.
- `git clone <repository-url>` - Clone an existing repository to your machine.
- `git remote add <name> <url>` - Add a remote repository.
- `git remote -v` - Show remote repositories.
- `git remote remove <name>` - Remove a remote repository.

### **Staging and Committing**
- `git add <file>` - Stage a file for commit.
- `git add .` - Stage all changes in the current directory.
- `git commit -m "message"` - Commit staged changes with a message.
- `git commit --amend` - Modify the last commit.

### **Branching**
- `git branch` - List branches.
- `git branch <branch-name>` - Create a new branch.
- `git checkout <branch-name>` - Switch to a branch.
- `git checkout -b <branch-name>` - Create and switch to a new branch.
- `git branch -d <branch-name>` - Delete a branch.
- `git branch -D <branch-name>` - Force delete a branch.

### **File System Navigation**
- `cd` - Change directory.
  - `cd ..` - Move to the parent directory.
  - `cd ~` (macOS/Linux) - Move to the home directory.
  - `cd \` (Windows) - Move to the root directory.
- `pwd` - Print working directory.
  - `pwd` (macOS/Linux).
  - `echo %cd%` (Windows).
- `ls` (macOS/Linux) / `dir` (Windows) - List directory contents.

### **File and Directory Operations**
- `mkdir` - Create a new directory.
- `rmdir` (Windows/macOS/Linux) - Remove an empty directory.
  - `rmdir /s` (Windows) - Remove a directory and its contents.
- `rm` (macOS/Linux) - Remove files or directories.
- `cp` (macOS/Linux) / `copy` (Windows) - Copy files or directories.
- `mv` (macOS/Linux) / `move` (Windows) - Move or rename files and directories.
- `ren` (Windows) - Rename files or directories.

### **Collaboration**
- `git pull` - Fetch and merge changes from the remote repository.
- `git fetch` - Download changes from the remote repository.
- `git push` - Push commits to a remote repository.
- `git push -u origin <branch-name>` - Push a branch and set upstream.

### **File Viewing**
- `cat` (macOS/Linux) / `type` (Windows) - Display the content of a file.
- `less` (macOS/Linux) - View a file one screen at a time.
- `head` (macOS/Linux) - Display the first few lines of a file.
- `tail` (macOS/Linux) - Display the last few lines of a file.

### **Undoing Changes**
- `git checkout <file>` - Discard changes in a specific file.
- `git reset <file>` - Unstage a file.
- `git reset --hard` - Reset working directory to the last commit.
- `git revert <commit>` - Revert a specific commit.

### **File Permissions**
- `chmod` (macOS/Linux) - Change file permissions.
- `chown` (macOS/Linux) - Change file ownership.

### **Process Management**
- `tasklist` (Windows) / `ps` (macOS/Linux) - List running processes.
- `taskkill` (Windows) - Terminate a process.
- `kill` (macOS/Linux) - Terminate a process.
- `top` (macOS/Linux) - Display system performance and running processes.

---
### Python 30 Days Guide + Practice Resources 
[Python in 30 Days](https://github.com/Asabeneh/30-Days-Of-Python/)

---
## **✅ Topics Covered**
- [My DevOps Learning](https://medium.com/@r.shara2922/my-devops-learning-fd00476566f3)

---
## 🔗 Resources and References
- [Official DevOps Handbook](https://devops-handbook.com/)
- [https://medium.com/@thisislong/linux-basics-file-permissions-792dbd7790ce]
- [https://chmod-calculator.com/]

