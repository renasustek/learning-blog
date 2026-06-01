---
title: git cheatsheet
date: 2026-06-01
---

**`git clone <url>`**
* **When to use it:** You want to download an existing repository from GitHub to your local machine.

**`git init`**
* **When to use it:** You are starting a brand-new project locally and need to track it with Git before pushing it online.

**`git status`**
* **When to use it:** Whenever you are confused. It tells you exactly what files are modified, staged, or untracked. Run this constantly.

**`git commit -m "message"`**
* **When to use it:** You have reached a logical stopping point and want to permanently save your staged changes locally.

**`git push origin <branch>`**
* **When to use it:** You are ready to upload your local commits to the remote repository so your team can see them.

**`git pull`**
* **When to use it:** You want to synchronise your local repository with the latest changes your team has pushed to the remote server.

**`git checkout -b <branch-name>`**
* **When to use it:** You are starting a new feature or fixing a bug, and you do not want to risk breaking the main codebase. This creates a new branch and switches to it instantly.

**`git checkout <branch-name>`**
* **When to use it:** You need to switch back to an existing branch.

**`git branch`**
* **When to use it:** You forgot what branch you are on, or you want to see a list of all local branches.

**`git merge <branch-name>`**
* **When to use it:** Your feature is complete, and you want to combine its code into your current branch (usually bringing your feature into `main`).

**`git stash`**
* **When to use it:** You are in the middle of working, but you urgently need to switch branches to look at something else. This temporarily shelves your uncommitted changes.

**`git reset --hard HEAD`**
* **When to use it:** You completely broke your current files and want to wipe out all uncommitted changes, reverting back to the exact state of your last commit. **Use with extreme caution.**
