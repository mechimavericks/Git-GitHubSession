# Git and GitHub Commands Reference

## Basic Git Commands

### Configuration
- `git config --global user.name "Your Name"` - Set username
- `git config --global user.email "your.email@example.com"` - Set email
- `git config --list` - List all configuration

### Repository Setup
- `git init` - Initialize a new repository
- `git clone <url>` - Clone a repository

### Basic Workflow
- `git status` - Show working tree status
- `git add <file>` - Add file to staging area
- `git add .` - Add all files to staging area
- `git commit -m "message"` - Commit with a message
- `git commit -am "message"` - Add tracked files and commit

### Viewing History
- `git log` - Show commit logs
- `git log --oneline` - Show commit history in one line per commit
- `git log --graph` - Show commit history as a graph
- `git diff` - Show changes between commits, commit and working tree, etc.

### Remote Operations
- `git remote -v` - List remote connections
- `git remote add <name> <url>` - Add remote repository
- `git push <remote> <branch>` - Push to remote repository
- `git pull <remote> <branch>` - Pull from remote repository
- `git fetch <remote>` - Download objects and refs from remote

## Intermediate Git Commands

### Branching and Merging
- `git branch` - List branches
- `git branch <branch-name>` - Create a new branch
- `git checkout <branch-name>` - Switch to a branch
- `git checkout -b <branch-name>` - Create and switch to a new branch
- `git switch <branch-name>` - Switch to a branch (Git 2.23+)
- `git merge <branch>` - Merge a branch into current branch
- `git branch -d <branch-name>` - Delete a branch
- `git branch -m <new-name>` - Rename current branch

### Undoing Changes
- `git restore <file>` - Discard changes in working directory
- `git restore --staged <file>` - Unstage changes
- `git reset HEAD~1` - Undo last commit, keeping changes
- `git reset --hard HEAD~1` - Undo last commit, discarding changes
- `git revert <commit>` - Create new commit that undoes specified commit

### Stashing
- `git stash` - Stash changes
- `git stash list` - List stashes
- `git stash apply` - Apply stashed changes
- `git stash pop` - Apply and remove stash
- `git stash drop` - Remove stash

## Advanced Git Commands

### Rewriting History
- `git commit --amend` - Modify last commit
- `git rebase <branch>` - Reapply commits on top of another branch
- `git rebase -i HEAD~n` - Interactive rebase of last n commits
- `git cherry-pick <commit>` - Apply specific commit to current branch
- `git reflog` - Show reference logs

### Advanced Inspection
- `git blame <file>` - Show who changed what and when in a file
- `git bisect start` - Start binary search for bad commits
- `git bisect good/bad` - Mark commits as good/bad during bisect

### Submodules and Subtrees
- `git submodule add <url>` - Add a submodule
- `git submodule update --init --recursive` - Initialize and update submodules
- `git subtree add --prefix=<path> <repository> <ref>` - Add repository as subtree

## GitHub Specific Commands

### Pull Requests (using GitHub CLI)
- `gh pr create` - Create a pull request
- `gh pr list` - List pull requests
- `gh pr checkout <number>` - Check out a pull request locally
- `gh pr review` - Review a pull request

### Issues
- `gh issue create` - Create an issue
- `gh issue list` - List issues
- `gh issue view <number>` - View an issue

### Fork Management
- `git remote add upstream <original-repo-url>` - Add original repository as upstream
- `git fetch upstream` - Fetch from upstream repository
- `git merge upstream/main` - Merge from upstream

### GitHub Actions
- `gh workflow list` - List workflows
- `gh workflow run <workflow>` - Run a workflow
- `gh workflow view <workflow>` - View a workflow

## Git Best Practices
- Use meaningful commit messages
- Commit often, push regularly
- Keep branches updated with main/master
- Use `.gitignore` to exclude files
- Set up branch protection rules
- Use semantic versioning for releases