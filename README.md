# Use Github - Learn Github

# Github Command
---

### 🔧 **Initialize & Configuration**
```bash
git init                      # Initialize a new Git repository
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

---

### 📥 **Clone Repository**
```bash
git clone https://github.com/username/repo-name.git
```

---

### 🔍 **Trạng thái & Log**
```bash
git status                   # Check current changes and staged files
git log                      # View commit history
git diff                     # See unstaged changes
```

---

### 📁 **Add, Commit, Push**
```bash
git add file.txt             # Add a specific file
git add .                    # Add all files
git commit -m "Your message" # Commit with message
git push origin main         # Push to remote (usually main or master)
```

---

### 🔄 **Pull & Fetch**
```bash
git pull origin main         # Pull latest changes from remote
git fetch                    # Fetch changes without merging
```

---

### 🌿 **Branch**
```bash
git branch                   # List branches
git branch new-branch        # Create new branch
git checkout new-branch      # Switch to branch
git checkout -b new-branch   # Create + switch in one line
git merge branch-name        # Merge branch into current
```

---

### 🚮 **Xóa & Đổi tên**
```bash
git branch -d branch-name         # Delete local branch
git push origin --delete branch-name  # Delete remote branch
git branch -m old-name new-name  # Rename branch
```

---

### 🐛 **Undo & Reset**
```bash
git restore file.txt         # Undo changes in file
git reset HEAD file.txt      # Unstage file
git reset --hard             # Reset all changes (careful!)
```

---

### 🔗 **Remote**
```bash
git remote -v                     # View remotes
git remote add origin <url>      # Add remote
git remote set-url origin <url>  # Change remote URL
```

### 🔗 **Remote file .git**
```bash
rm -rf .git
```

---

