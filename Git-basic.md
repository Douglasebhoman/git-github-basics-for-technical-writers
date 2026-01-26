# Git Basics

This document explains Git in depth for beginners, technical writers, and non-developers who need to work confidently in repositories.

---

## What Is Git?

Git is a **distributed version control system**. It tracks changes to files over time, allowing you to:

* See what changed
* Understand who changed it
* Restore earlier versions
* Collaborate safely with others

Unlike cloud-only tools, Git works **locally on your computer** and syncs changes when you decide.

---

## Why Git Matters for Technical Writers

Git is not just for developers. For writers, Git enables:

* Version history for documentation
* Collaboration without overwriting work
* Structured reviews through pull requests
* Docs-as-code workflows

Using Git turns documentation into a **managed system**, not a collection of files.

---

## Key Git Concepts (Must Know)

### Repository (Repo)

A repository is a project folder tracked by Git. It contains:

* Your files
* A hidden `.git` directory that stores history

### Commit

A commit is a **snapshot** of your project at a specific moment.

Each commit:

* Has a unique ID
* Includes a message describing the change
* Can be revisited or reversed

### Branch

A branch is an independent line of work.

Common branches:

* `main` – stable, published content
* `feature/docs-update` – work in progress

Branches allow experimentation without breaking the main content.

### Working Directory, Staging Area, Repository

Git tracks changes in three stages:

1. **Working directory** – where you edit files
2. **Staging area** – files prepared for commit
3. **Repository** – committed history

This separation gives you control over what gets saved.

---

## Core Git Workflow

A basic Git workflow looks like this:

1. Edit files
2. Stage changes
3. Commit changes
4. Push to remote repository

Repeat this cycle consistently.

---

## Essential Git Commands

### Initialize a Repository

```bash
git init
```

Creates a new Git repository in the current folder.

---

### Check Status

```bash
git status
```

Shows which files are:

* Modified
* Staged
* Untracked

This is the safest command to run anytime.

---

### Stage Files

```bash
git add filename.md
```

Stages a specific file.

```bash
git add .
```

Stages all changes.

---

### Commit Changes

```bash
git commit -m "Add Git basics documentation"
```

Creates a snapshot with a clear message.

---

### View History

```bash
git log
```

Displays commit history.

---

## Git vs GitHub (Important Distinction)

| Git                    | GitHub                  |
| ---------------------- | ----------------------- |
| Version control system | Hosting platform        |
| Runs locally           | Cloud-based             |
| Tracks changes         | Stores and shares repos |
| Works offline          | Requires internet       |

You use **Git** to manage changes.
You use **GitHub** to share and collaborate.

---

## Common Git Mistakes (and How to Avoid Them)

* **Skipping commit messages** → Always describe *why* the change was made
* **Committing everything blindly** → Review staged files
* **Working on main directly** → Use branches for safety

---

## Best Practices for Writers

* Commit small, logical changes
* Write clear commit messages
* Use Markdown for documentation
* Keep `main` clean and stable
* Review changes before pushing

---

## Summary

Git gives you:

* Control over your documentation
* Confidence to experiment
* A professional documentation workflow

Mastering Git basics is a foundational skill for modern technical writers.

---

**Next document:** `/docs/github-basics.md` – understanding GitHub and collaboration
