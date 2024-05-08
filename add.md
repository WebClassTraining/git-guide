# Git Add

## Overview

The `git add` command adds new or changed files in your working directory to the Git staging area. It allows you to select specific files or directories to include in the next commit.

## When to Use `git add`

As you're working, you change and save files. Before committing these changes, you use `git add` to select which changes to include in the next commit. This allows you to shape your commits and history systematically.

## What Does `git add` Do?

`git add [filename]` selects the specified file and moves it to the staging area, marking it for inclusion in the next commit. You can select all files, a directory, specific files, or even specific parts of a file for staging and commit.

## How to Use `git add`

### Common usages and options for `git add`

- `git add <path>`: Stage a specific directory or file.
- `git add .`: Stage all files in the entire repository.
- `git add -p`: Interactively stage hunks of changes.

You can see all options with `git add` in [git-scm's documentation](https://git-scm.com/docs/git-add).

### Examples of `git add`

#### Basic Usage

```bash
git add README.md //filename
```
or

```bash
git add .    //adds the entire directory
```

or

```bash
git add -A  // including files in the current directory and in higher directories
```

or

```bash
git add -u  // stages modified and deleted files only, NOT new files
```

### Examples of `git reset`

To undo changes in the staging area and move them back to the working directory, you can use `git reset` with the `HEAD` parameter:

```bash
git reset HEAD file.txt
```

or

```bash
git reset --hard
```
