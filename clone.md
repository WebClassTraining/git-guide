# Git Clone

## Overview

The `git clone` command is used to create a copy of a specific repository or branch within a repository. It allows you to clone an entire repository - all files, branches, and commits.

## What Does `git clone` Do?

When you clone a repository with Git, you get the entire repository, not just one file. This includes all files, branches, and commits. Cloning is typically done once, at the beginning of your interaction with a project.

## How to Use `git clone`

### Common usages and options for `git clone`

- `git clone [url]`: Clone (download) a repository that already exists on GitHub.
- `git clone --mirror`: Clone a repository without the ability to edit any files, including all branches.
- `git clone --single-branch`: Clone only a single branch.
- `git clone --sparse`: Populate only the files present in the root directory.
- `git clone --recurse-submodules[=<pathspec>]`: Initialize and clone submodules based on the provided pathspec.

You can see all options with `git clone` in [git-scm's documentation](https://git-scm.com/docs/git-clone).

### Examples of `git clone`

#### Basic Clone

```bash
git clone https://github.com/github/training-kit.git

```
or

```bash
git clone git@github.com:WebClassTraining/git-guide.git
```
