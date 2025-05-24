# Git & GitHub Workshop Syllabus

**Organized by:** Mechi Mavericks  
**Mode:** In-Person Hands-On Workshop  

---

## Workshop Objective

This workshop aims to help students with the foundational knowledge and practical skills to use Git and GitHub for version control and team collaboration in software development. By the end of the workshop, participants will be able to:

- Understand the concepts and benefits of version control.
- Use Git for tracking and managing source code changes locally.
- Collaborate on projects using GitHub, including pull requests, code reviews, and branch management.

---

## Syllabus Overview

### **Day 1: Introduction to Git (Local Version Control)**

#### What is Version Control?
- Explanation with real-world examples.
- Centralized vs Distributed version control systems.

#### Importance in Software Development
- Enables collaboration, backup, and history tracking.

#### Introduction to Git
- Brief history and significance.
- Comparison with other systems (e.g., SVN, Mercurial).
- Key concepts: repository, commit, branch, merge.

#### Installation
- Step-by-step installation for Windows/Linux/macOS.

#### User Configuration
```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
```

#### Essential Git Commands
- `git init`, `git status`, `git add`, `git commit`, `git log`

#### Hands-On Practice
- Creating a new project folder.
- Initializing Git and tracking file changes.
- Committing with proper messages.
- Viewing commit history.

---

### **Day 2: Introduction to GitHub and Collaboration**

#### What is GitHub?
- GitHub as a cloud platform for Git repositories.
- Introduction to repositories, branches, pull requests, and issues.

#### Setting Up GitHub
- Creating a GitHub account.
- Setting up the GitHub account.

#### Connecting Git with GitHub
- Creating a new repository on GitHub.
- Linking local repo to remote using:
```bash
git remote add origin <repository-URL>
```
- Pushing code using:
```bash
git push -u origin main
```

#### Collaborative Commands
- Cloning repositories using `git clone`.
- Creating and switching branches using `git branch` and `git checkout`.

#### Pull Requests and Code Review
- Creating and managing pull requests on GitHub.
- Reviewing and merging changes.
- Resolving merge conflicts.

#### Hands-On Practice
- Each participant clones a shared repository.
- Students create feature branches and push updates.
- Teams submit pull requests for peer review.
- Practice merging changes and resolving conflicts.
- Simulate real-world team collaboration.

---

## Tools Required

- A laptop with Git installed (will be taught during the session)
- VS Code or any code editor
- GitHub account
- Internet connectivity (for Day 2)

---

## Expected Outcomes

By the end of this workshop, students will:

- Understand and use Git for version control in local projects.
- Create and manage GitHub repositories.
- Collaborate effectively on shared codebases.
- Resolve conflicts and contribute through pull requests.
