 
# 📘 Git Beginner Guide

This repository contains basic Git commands and workflow for beginners.
It helps you understand how to use Git step by step.

---
# 🚀 What is Git?

Git is a version control system that helps you:
- Track changes
- Manage projects
- Work with teams
- Push code to GitHub

---

# 📂 1️⃣ Initialize a Git Repository

```bash
git init
````

This creates a new Git repository in your project folder.

---

# 📋 2️⃣ Check Status

```bash
git status
```

Shows modified, staged, and untracked files.

---

# ➕ 3️⃣ Add Files

Add one file:

```bash
git add filename
```

Add all files:

```bash
git add .
```

---

# 💾 4️⃣ Commit Changes

```bash
git commit -m "Your commit message"
```

Example:

```bash
git commit -m "Added login feature"
```

---

# 🔗 5️⃣ Connect to GitHub

Add remote repository:

```bash
git remote add origin https://github.com/your-username/repository-name.git
```

Push code:

```bash
git push -u origin main
```

---

# 🔄 6️⃣ Pull Latest Updates

```bash
git pull origin main
```

---

# 🌿 7️⃣ Branching

Create new branch:

```bash
git branch feature-name
```

Switch branch:

```bash
git checkout feature-name
```

Create & switch:

```bash
git checkout -b feature-name
```

Merge branch:

```bash
git merge feature-name
```

---

# ❌ 8️⃣ Undo Changes

Restore file:

```bash
git restore filename
```

Unstage file:

```bash
git reset HEAD filename
```

---

# 🔥 Complete Basic Workflow

```bash
git init
git add .
git commit -m "First commit"
git branch -M main
git remote add origin https://github.com/your-username/repository-name.git
git push -u origin main
```

 
# 🎯 Learning Purpose

This project helps practice:

* Git basics
* GitHub integration
* Branching workflow
* Version control concepts
 
