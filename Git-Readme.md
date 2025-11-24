# Git Commands Reference for DevOps

This is a comprehensive reference guide for commonly used Git commands, their purposes, and examples. Ideal for DevOps workflows and version control.

---

## 1️⃣ git init
**Purpose:** Initialize a new Git repository.  
**Example:**
```bash
mkdir my_project
cd my_project
git init
````

Creates a `.git` folder to start tracking changes in the project.

---

## 2️⃣ git clone

**Purpose:** Copy an existing repository to your local machine.
**Example:**

```bash
git clone https://github.com/user/repo.git
```

Downloads the repo and sets up the remote connection automatically.

---

## 3️⃣ git pull

**Purpose:** Fetch and merge changes from a remote repository into your current branch.
**Example:**

```bash
git pull origin main
```

* `origin` = remote name
* `main` = branch name

---

## 4️⃣ git push

**Purpose:** Upload your local commits to a remote repository.
**Example:**

```bash
git push origin main
```

---

## 5️⃣ git commit

**Purpose:** Save staged changes to the local repository with a descriptive message.
**Example:**

```bash
git add .
git commit -m "Initial commit"
```

---

## 6️⃣ git log

**Purpose:** View commit history.
**Example:**

```bash
git log
```

Shows commit hash, author, date, and message.

---

## 7️⃣ git diff

**Purpose:** See the difference between files in your working directory and the last commit.
**Example:**

```bash
git diff
```

---

## 8️⃣ git config

**Purpose:** Configure Git settings (username, email, editor, etc.).
**Example:**

```bash
git config --global user.name "John Doe"
git config --global user.email "john@example.com"
```

---

## 9️⃣ git merge

**Purpose:** Combine changes from one branch into another.
**Example:**

```bash
git checkout main
git merge feature-branch
```

---

## 🔟 git add

**Purpose:** Stage changes before committing.
**Example:**

```bash
git add file1.txt
git add .
```

* `. ` stages all changed files.

---

## 1️⃣1️⃣ git cherry-pick

**Purpose:** Apply a specific commit from another branch to your current branch.
**Example:**

```bash
git checkout main
git cherry-pick a1b2c3d4
```

* `a1b2c3d4` = commit hash

---

## 1️⃣2️⃣ git fetch

**Purpose:** Download changes from the remote repository without merging.
**Example:**

```bash
git fetch origin
```

Allows you to review changes before merging.

---

## 1️⃣3️⃣ git rebase

**Purpose:** Reapply commits on top of another branch for a cleaner history.
**Example:**

```bash
git checkout feature-branch
git rebase main
```

---

## 1️⃣4️⃣ git revert

**Purpose:** Undo a specific commit by creating a new commit (safe undo).
**Example:**

```bash
git revert a1b2c3d4
```

---

## 1️⃣5️⃣ git hash-object

**Purpose:** Create a Git object from a file and get its SHA-1 hash.
**Example:**

```bash
git hash-object file1.txt
```

---

## Notes

* `origin` refers to the default remote repository name.
* `main` is the default branch in most repositories.
* Use `git add` to stage changes before committing with `git commit`.
* `git fetch` + `git merge` = `git pull`.

---

**This guide is a single-file reference for Git commands, suitable for beginners and DevOps practitioners.**

