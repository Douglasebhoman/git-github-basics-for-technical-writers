# GitHub Basics

This document explains GitHub for beginners and technical writers who need to collaborate, publish documentation, and build a professional portfolio.

---

## What Is GitHub?

GitHub is a **cloud-based hosting platform** for Git repositories. It allows individuals and teams to:

* Store and share code or documentation
* Collaborate with others
* Review changes before publishing
* Showcase work publicly

GitHub does **not replace Git**. It works *with* Git.

---

## Why GitHub Matters for Technical Writers

For technical writers, GitHub is important because it enables:

* Public documentation portfolios
* Structured collaboration with developers
* Review workflows (pull requests)
* Issue tracking for documentation tasks
* Docs-as-code publishing

Many companies expect writers to understand GitHub fundamentals.

---

## Key GitHub Concepts

### Repository

A GitHub repository is the **remote version** of your local Git project.

It contains:

* Files and folders
* Commit history
* Branches
* Issues and pull requests

Repositories can be **public** or **private**.

---

### Remote

A remote is a link between your local Git repository and GitHub.

Common remote name:

* `origin`

This connection allows you to push and pull changes.

---

### Branches on GitHub

Branches on GitHub mirror Git branches.

Common usage:

* `main` – stable documentation
* Feature branches – new or updated docs

Branches protect the main content from accidental changes.

---

### Pull Request (PR)

A pull request is a **request to merge changes** from one branch into another.

PRs allow:

* Review before publishing
* Comments and suggestions
* Approval workflows

For writers, PRs are often used for:

* Documentation updates
* Content reviews
* Style corrections

---

### Issues

Issues are used to:

* Track bugs
* Request documentation updates
* Assign tasks
* Discuss improvements

Writers often use issues to manage documentation work.

---

## Basic GitHub Workflow

A typical GitHub workflow:

1. Create or clone a repository
2. Create a branch
3. Make changes locally
4. Commit changes
5. Push to GitHub
6. Open a pull request
7. Review and merge

This workflow ensures quality and accountability.

---

## Essential GitHub Actions

### Create a Repository

* Click **New Repository** on GitHub
* Add a name and description
* Choose public or private
* Initialize with README (optional)

---

### Clone a Repository

```bash
git clone repository-url
```

Creates a local copy of a GitHub repository.

---

### Push Changes

```bash
git push origin branch-name
```

Uploads local commits to GitHub.

---

### Pull Changes

```bash
git pull
```

Fetches and merges changes from GitHub.

---

## GitHub for Documentation Projects

Common documentation uses:

* Hosting Markdown documentation
* Managing doc updates via PRs
* Publishing docs with static site generators
* Showcasing writing samples

GitHub becomes both a **workspace** and a **portfolio**.

---

## Best Practices for Writers

* Keep repositories organized
* Write clear commit and PR descriptions
* Use issues to track doc tasks
* Review changes before merging
* Keep documentation up to date

---

## Summary

GitHub enables collaboration, visibility, and professionalism.

For technical writers, understanding GitHub is essential for working in modern documentation teams and building a credible portfolio.

---

**Next document:** `/docs/workflows.md` – Git + GitHub workflows for documentation
