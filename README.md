# A Beginner's Guide to Git Commands

## Project Overview

This project is a practicxal beginner's guide to using Git. It helps new users understand what Git is, how to set it up, and how manage changes with basic Git commands.

## What You'll Learn

- What Git is and why it is useful
- How to install and configure Git
- How to use basic Git commands
- Examples of common Git operations

## Team Members

- Diego Roldan - Git Introduction and Setup
- Tracy - Basic Git Commands

## Project Structure

This guide is divided into two main sections:

1. [Git Introduction and Setup](git-setup.md)
2. Basic Git Commands and Examples

## Part 2: Basic Git Commands and Examples

Git commands allow developers to create repositories, track changes, save work, and share updates with others. The following commands are commonly used in a basic Git workflow.

### `git init`

The `git init` command creates a new Git repository in the current folder. It allows Git to begin tracking changes made to the project.

Example:

```bash
git init

```

Use this command when starting a new local project that is not already a Git repository.

### `git status`

The `git status` command shows the current state of the repository. It identifies files that are untracked, modified, or staged for the next commit.

Example:


```bash
git status
```

This command is useful for checking what has changed before staging or committing files.

### `git add`

The `git add` command places changes into the staging area so they can be included in the next commit.

To stage one specific file:

```bash
git add README.md
```

To stage all changes in the current project:

```bash
git add .
```

Staging allows developers to choose which changes will be included in the next commit.

###`git commit`

The `git commit` command saves the staged changes as a snapshot in the local Git repository. Each commit should include a clear message that explains the purpose of the changes.

Example:

```bash
git commit -m "Add basic Git commands section"
```

A commit records the changes locally, but it does not upload them to GitHub.

### `git push`

The `git push` command uploads committed changes from the local repository to a remote repository such as GitHub.

Example:

```bash
git push origin main
```

In this example, `origin` refers to the remote repository and `main` is the branch being pushed.

### `git pull`

The `git pull` command retrieves changes from a remote repository and combines them with the current local branch.

Example:

```bash
git pull origin main
```

This command is useful when other contributors have updated the remote repository and you need the latest version before continuing your work.

### Basic Git Workflow Example

A common Git workflow follows these steps:

1. Check the current repository status:

```bash
git status
```

2. Stage the files you want to include in the next commit:

```bash
git add .
```

3. Save the staged changes with a descriptive commit message:

```bash
git commit -m "Update project files"
```

4. Upload the committed changes to GitHub:

```bash
git push origin main
```

5. Before starting new work, retrieve the latest changes from GitHub:

```bash
git pull origin main
```

Using these commands in sequence helps developers track changes, save progress, and keep local and remote repositories synchronized.