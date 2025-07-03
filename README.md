🛠️ Standard Git Workflow
🧱 1. Initialize or Clone a Repository
If starting a new project:
```bash
git init
```
If working on an existing project from GitHub:
```bash
git clone <repository_url>
```

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
