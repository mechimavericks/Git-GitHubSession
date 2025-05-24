# Git and GitHub Exercises

This file contains practical exercises to help you master Git and GitHub. Each exercise builds on skills learned in previous ones and provides hands-on experience with key version control concepts.

## Beginner Level Exercises

### Exercise 1: Setting Up Your First Repository
**Objective**: Create a local Git repository and make your first commits

1. Create a new directory called "my-first-repo"
2. Initialize it as a Git repository
3. Create a file called "README.md" with a brief description of the repository
4. Add and commit the file with an appropriate message
5. Make changes to the README.md file
6. View the differences between the working directory and the last commit
7. Commit the changes with a new message

### Exercise 2: Working with Remote Repositories
**Objective**: Connect your local repository to GitHub

1. Create a new repository on GitHub (without initializing it)
2. Connect your local "my-first-repo" to the GitHub repository
3. Push your commits to GitHub
4. Make changes locally and push them
5. Make a change directly on GitHub
6. Pull the changes to your local repository

### Exercise 3: Basic Git Workflow
**Objective**: Practice the basic Git workflow with multiple files

1. Create three new files in your repository: "file1.txt", "file2.txt", and "file3.txt"
2. Add content to each file
3. Stage only file1.txt and file2.txt
4. Create a commit with only those files
5. Stage and commit file3.txt separately
6. View the commit history
7. Push all commits to GitHub

## Intermediate Level Exercises

### Exercise 4: Branching and Merging
**Objective**: Work with branches to develop features independently

1. Create a new branch called "feature-x"
2. Switch to the feature branch
3. Make at least three commits on this branch
4. Switch back to the main branch
5. Create and switch to another branch called "feature-y"
6. Make different changes on this branch
7. Merge "feature-x" into main
8. Resolve any conflicts if they occur
9. Delete the "feature-x" branch

### Exercise 5: Collaborative Workflow
**Objective**: Practice collaboration using forks and pull requests

1. Find a partner or use a second GitHub account
2. Fork your partner's repository
3. Clone your fork locally
4. Create a feature branch
5. Make meaningful changes
6. Push your branch to your fork
7. Create a pull request to the original repository
8. Review a pull request from someone else
9. Suggest changes or approve and merge

### Exercise 6: Merge Conflict Resolution
**Objective**: Deliberately create and resolve merge conflicts

1. Create a new branch called "conflict-branch"
2. Modify a specific line in a file
3. Commit the changes and push to GitHub
4. Switch to main and modify the same line differently
5. Commit the changes
6. Try to merge "conflict-branch" into main
7. Resolve the resulting conflict
8. Complete the merge
9. Document the steps you took to resolve the conflict

## Advanced Level Exercises

### Exercise 7: Rewriting History
**Objective**: Learn to modify Git history safely

1. Create a branch called "history-rewrite"
2. Make a commit with a typo in the message
3. Fix the commit message using amend
4. Make three small related commits
5. Use interactive rebase to squash them into a single, clean commit
6. Make a commit on main that you "accidentally" want to include in your branch
7. Cherry-pick that commit to your branch
8. Force push your branch to GitHub (note: normally avoid force pushing to shared branches)

### Exercise 8: Git Hooks
**Objective**: Implement Git hooks to automate tasks

1. Navigate to the .git/hooks directory in your repository
2. Create a pre-commit hook that checks for trailing whitespace
3. Make it executable
4. Test it by attempting to commit a file with trailing whitespace
5. Create a commit-msg hook that ensures commit messages are at least 10 characters
6. Test the hook with both valid and invalid commit messages

### Exercise 9: GitHub Actions
**Objective**: Set up continuous integration using GitHub Actions

1. Create a simple application (or use an existing one)
2. Add appropriate tests
3. Create a .github/workflows directory
4. Add a YAML file defining a basic CI workflow that:
   - Runs on push to main and on pull requests
   - Sets up the necessary environment
   - Installs dependencies
   - Runs tests
   - Reports success/failure
5. Push the workflow to GitHub
6. Create a pull request to trigger the workflow
7. Check the Actions tab to see the workflow running

### Exercise 10: Git Submodules and Advanced Features
**Objective**: Work with submodules and other advanced Git features

1. Create two separate repositories: "main-project" and "library"
2. Add some code to "library"
3. Add "library" as a submodule of "main-project"
4. Make changes to the library and update the main project
5. Practice using git bisect to find a commit that introduces a specific change
6. Use git blame to identify who changed specific lines in a file and when

## Challenge Exercise

### Exercise 11: Complete Project Simulation
**Objective**: Simulate a complete team workflow on a small project

1. Form a team of 3-4 people
2. Create a shared repository
3. Set up branch protection rules requiring pull request reviews
4. Establish a branching strategy (e.g., GitFlow)
5. Assign tasks to team members
6. Implement the tasks on feature branches
7. Create pull requests and conduct code reviews
8. Merge completed features
9. Tag a release version
10. Handle a hotfix for the release
11. Document the entire process and any challenges encountered