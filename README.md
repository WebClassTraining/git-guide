# Git User Guide

## Table of Contents

1. [Introduction](#introduction)
2. [Downloading Git](https://git-scm.com/download/win)
3. [Installing Git](install.md)
4. [Configuring Git](config.md)
5. [Init](init.md)
6. [Clone](clone.md)
7. [Add](add.md)
8. [Commit](commit.md)
9. [Remote](remote.md)
10. [Status](status.md)
11. [Pull](pull.md)
12. [Push](push.md)


## Introduction

Git is a free and open-source distributed version control system designed to handle everything from small to very large projects with speed and efficiency. It allows multiple developers to work on the same project simultaneously, providing features such as branching, merging, and version tracking.

This guide will help you get started with Git by providing step-by-step instructions on how to download, install, and configure Git on your system, as well as basic usage examples.

## Setting Up Git

To start using Git, follow these steps:

1. **Install Git**: Download and install Git from the official website: <https://git-scm.com/downloads>
2. **Create a new repository**: Open Git Bash (or your operating system's equivalent) and run the command `git init`. This will create a new
directory called `.git` in your current working directory.
3. **Make changes to your files**: Create some sample files or modify existing ones to demonstrate how Git tracks changes.

## Basic Git Commands

### 1. Adding Files

* `git add <file_name>`: Stage a file for the next commit. For example, `git add README.md`
* `git add .`: Stage all files in the current directory and its subdirectories.

### 2. Committing Changes

* `git commit -m "Initial commit"`: Commit your staged changes with a meaningful commit message.

### 3. Viewing History

* `git log`: View a list of all commits made to this repository, including dates and descriptions.
* `git log --graph`: Visualize the commit history as a graph.

### 4. Creating a Branch

* `git branch <branch_name>`: Create a new branch based on the current branch. For example, `git branch feature/new-feature`
* `git checkout <branch_name>`: Switch to the specified branch. For example, `git checkout feature/new-feature`

### 5. Merging Changes

* `git merge <branch_name>`: Merge changes from another branch into your current branch. For example, `git merge feature/new-feature`
* `git merge --no-commit`: Merge changes without committing them.

## Advanced Topics (Optional)

* **Remote repositories**: Connect to a remote repository using `git remote add origin <repository_url>`
* **Pushing and pulling**: Push local changes to a remote repository with `git push -u origin master`, or pull changes from the remote
repository with `git pull origin master`

[Next](install.md)
