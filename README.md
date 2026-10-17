# A Beginner's Guide to Git Commands

## Project Overview

This project is a beginner-friendly guide to Git. Our goal is to help new users understand what Git is, how to set it up, and how to use basic Git commands.

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

1. Git Introduction and Setup
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