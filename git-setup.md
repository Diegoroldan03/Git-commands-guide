
# Introduction to Git

## What Is Git?

Git is a version control system that helps developers track changes in their projects. It allows to save different versions of the work and go back to previous versions if something goes wrong.

## Why Is Git Useful?

Git is useful because it makes it easier to manage projects, especially when working with other people.

Some of its main benefits include:

- Tracking changes made to files
- Keeping a history of previous versions
- Working on different parts of a project using branches
- Collaborating with other developers without overwriting their work

For example, if two people are working on the same website, one might be fixing bugs while the other is adding new features. With Git, they can work on their own branches without affecting each other's changes. When they're done, they can review their work and combine everything into the main project.


## How to Install Git

Before you can start using Git, you need to install it on your computer. The installation only takes a few steps.

### Installing Git on Windows

1. Visit the official Git website at https://git-scm.com/downloads
2. Select Windows and download the installer.
3. Open the downloaded file and follow the installation instructions.
4. Keep the default settings if you're not sure which options to choose.
5. Once the installation is complete, open PowerShell or the terminal in VS Code.

### Checking the Installation

To check if Git was installed correctly, open your terminal and enter:

`git --version`

If Git is installed, you should see a version number, such as `git version 2.51.0`.

You can also find instructions for macOS and Linux on the official Git website.


## How to Configure Git

After installing Git, the next step is to set up your name and email address. Git uses this information to identify who made each commit in a project.

### Setting Up Your Name and Email

Open PowerShell or the terminal in VS Code and enter these commands:

**Set your name:**

`git config --global user.name "Your Name"`

**Set your email:**

`git config --global user.email "you@example.com"`

Replace "Your Name" and "you@example.com" with your own information. If you're using GitHub, you can use the email connected to your account or your GitHub private email address.

The `--global` option means Git will use these settings for all repositories on your computer, so you don't have to enter them every time you start a new project.

### Checking Your Configuration

To make sure everything was saved correctly, you can check your settings with these commands:

`git config --global user.name`

`git config --global user.email`

Git should display the name and email you entered earlier.

You can also view all your Git settings by running:

`git config --list`

Once your name and email are configured, you're ready to start using Git to track changes in your projects.
