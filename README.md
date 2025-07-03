Git has many commands used to manage code versions, collaborate with others, and track changes in your project. Here's a categorized list of commonly used Git commands:


Standard Git Workflow:

1. Initialize or Clone a Repository
If starting a new project:
    git init
If working on an existing project from GitHub:
    git clone <repository_url>
2. Check the Status of Files
See what's changed or staged:
    git status
3. Create a Branch (Optional but Recommended)
Create and switch to a new branch for a feature or bugfix:
    git checkout -b feature-branch-name
4. Make Changes and Stage Them
After editing files, stage the files you want to commit:
    git add <file_name>         # stage one file
    git add .                   # stage all files
5. Commit the Changes
Save a snapshot of your changes with a message:
    git commit -m "Meaningful commit message"
6. Pull Latest Changes from Remote (Before Pushing)
Update your branch with the latest remote changes:
    git pull origin main        # or whatever branch you're working with
7. Push the Changes to Remote Repository
Send your commits to GitHub or another remote:
    git push origin feature-branch-name
8. Create a Pull Request (PR)
Go to GitHub and open a Pull Request from your branch to the main branch.
9. Merge the Branch
After approval/review, merge it:
On GitHub (via PR), or
Locally:
    git checkout main
    git pull
    git merge feature-branch-name
    git push origin main
10. Delete the Feature Branch
Clean up the old branch:
    git branch -d feature-branch-name       # delete local branch
    git push origin --delete feature-branch-name  # delete remote branch


   


🚀 Basic Git Commands
| Command                   | Description                                                  |
| ------------------------- | ------------------------------------------------------------ |
| `git init`                | Initialize a new Git repository                              |
| `git clone <url>`         | Copy (clone) a repository from GitHub or another remote      |
| `git status`              | Show the status of changes (tracked/untracked, staged, etc.) |
| `git add <file>`          | Add file(s) to the staging area                              |
| `git add .`               | Add **all** changed files to staging                         |
| `git commit -m "message"` | Commit staged changes with a message                         |
| `git log`                 | Show the commit history                                      |
| `git diff`                | Show the changes not yet staged                              |
| `git diff --staged`       | Show the changes that are staged for the next commit         |


🌐 Remote Repositories

| Command                       | Description                           |
| ----------------------------- | ------------------------------------- |
| `git remote -v`               | Show remote URL(s)                    |
| `git remote add origin <url>` | Add a remote repository               |
| `git push`                    | Push commits to the remote repository |
| `git push -u origin <branch>` | Push and set the upstream branch      |
| `git pull`                    | Fetch and merge changes from remote   |
| `git fetch`                   | Fetch latest changes but don’t merge  |



Connect to Remote Repositories :

Git connects your local code to online repositories like GitHub, GitLab, or Bitbucket:

Backup your code in the cloud.

Share code with others.

Example: git remote, git push, git fetch.
