# 🧰 Common Git Commands Cheat Sheet

Here’s a quick reference of the main Git commands with short explanations.

---

## 🏁 Setup and Configuration

```bash
git config --global user.name "Your Name"     # Set your Git username
git config --global user.email "you@example.com"  # Set your Git email
git config --list                             # Show current Git configuration
```

---

## 📦 Creating and Cloning Repositories

```bash
git init                                      # Initialize a new local Git repository
git clone <url>                               # Clone an existing repository from GitHub
```

---

## 🔍 Checking Status and Logs

```bash
git status                                    # Show current status of the repository
git log                                       # Show commit history
git log --oneline                             # Show concise commit history
```

---

## 💾 Staging and Committing Changes

```bash
git add <file>                                # Stage specific file
git add .                                     # Stage all changes in the current directory
git commit -m "commit message"                # Commit staged changes with a message
git commit -am "commit message"               # Stage and commit all tracked files
```

---

## 🔄 Branching and Merging

```bash
git branch                                    # List all branches
git branch <name>                             # Create a new branch
git checkout <name>                           # Switch to another branch
git checkout -b <name>                        # Create and switch to a new branch
git merge <branch>                            # Merge another branch into the current one
```

---

## 🚀 Working with Remotes

```bash
git remote -v                                 # List remote repositories
git remote add origin <url>                   # Add a new remote repository
git push -u origin <branch>                   # Push changes to remote for the first time
git push                                      # Push changes to remote
git pull                                      # Fetch and merge changes from remote
git fetch                                     # Download changes without merging
```

---

## 🧹 Undoing Changes

```bash
git restore <file>                            # Undo changes in a file (not staged)
git reset <file>                              # Unstage a file but keep changes
git reset --hard                              # Discard all changes since last commit
git revert <commit>                           # Create a new commit that undoes a previous one
```

---

## 🧠 Helpful Tips

```bash
git diff                                      # Show changes not yet staged
git diff --staged                             # Show changes staged for commit
git stash                                     # Save changes temporarily
git stash pop                                 # Restore stashed changes
```

---

✅ **Pro Tip:** Always pull (`git pull`) before pushing new changes to avoid conflicts.
