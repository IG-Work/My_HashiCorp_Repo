# My_HashiCorp_Repo
HashiCorp Repo for the testing of the Training

## This is the repo created for the Dimpy to check and verify.

## Below are the deatsils of the git commands I have referred so far and listed for the review

## Git Configuration & Setup

```sh
git config --global user.name "Your Name"  # Set your username globally
git config --global user.email "youremail@example.com"  # Set your email globally
git config --global color.ui auto  # Enable colored output
git help  # Show Git help documentation
```

## Initializing a Repository

```sh
git init  # Initialize a new Git repository
git init <directory>  # Create a new Git repository in a specific directory
git clone <repository_url>  # Clone a repository
git clone --branch <branch_name> <repository_url>  # Clone a specific branch
```

## Basic Git Commands

```sh
git add <file>  # Add a specific file to the staging area
git add .  # Add all modified and new files to the staging area
git status  # Show repository status
git diff  # Show changes between working directory and staging area
git commit -m "<message>"  # Create a commit with a message
git reset <commit>  # Reset to a specific commit
git rm <file>  # Remove a file from repository
git mv <old> <new>  # Rename or move a file
```

## Branching and Merging

```sh
git branch  # List branches
git branch <branch-name>  # Create a new branch
git checkout <branch-name>  # Switch to a branch
git merge <branch>  # Merge a branch
git stash  # Stash changes
git stash pop  # Apply and remove the most recent stash
git tag <tag-name>  # Create a lightweight tag
```

## Remote Repositories

```sh
git fetch  # Retrieve changes from a remote repository
git pull  # Fetch and merge changes
git push  # Push local commits to a remote repository
git remote add <name> <url>  # Add a new remote repository
```

## Git History & Comparison

```sh
git log  # View commit history
git show <commit>  # Show details of a commit
git revert <commit>  # Revert a commit
git rebase <branch>  # Reapply commits on top of another branch
```

