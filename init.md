# Git init

## What Does `git init` Do?

`git init` turns any directory into a Git repository. When you initialize a repository with `git init`, Git creates a hidden directory called `.git` that stores all of the objects and references used in your project's history. This directory separates a regular directory from a Git repository.

## How to Use `git init`

### Common usages and options for `git init`

- `git init`: Transform the current directory into a Git repository.
- `git init <directory>`: Transform a directory in the current path into a Git repository.
- `git init --bare`: Create a new bare repository (a repository used as a remote repository only, without active development).

You can see all of the options with `git init` in [git-scm's documentation](https://git-scm.com/docs/git-init).

## Examples of `git init`

### `git init` vs `git clone`

- **`git init`: One Person Starting a New Repository Locally**
  - Initialize the repository and make at least one commit.
  - Create a remote repository (e.g., on GitHub.com).
  - Add the remote URL to your local git repository with `git remote add origin <URL>`.
  - Stage existing files with `git add` and commit with `git commit`.
  - Push to the remote with `git push -u origin master`.

- **`git clone`: The Remote Already Exists**
  - If the repository already exists on a remote, use `git clone`.
  - If there are no commits in the remote repository, follow the steps for `git init`.
  - If there are commits and files in the remote repository, clone the repository, move project files, commit changes, and push.

### `git init` Existing Folder

- The default behavior of `git init` is to transform the current directory into a Git repository.
- Navigate into the targeted root directory of an existing project and run `git init`.
- Or, create a new repository in a directory in your current path using `git init <directory>`.

## `git init` Gone Wrong

- **Running `git init` in the wrong directory**: This may create unintended repositories. To fix, track down and remove the unintended repository using `rm -rf .git`.
- **Related Terms**: `git clone`, `git status`, `git remote -v`, `git remote add origin <url>`, `git push`, `git push -u origin master`.

For more details, refer to the [git-scm documentation](https://git-scm.com/doc).

[Previous](install.md) | [Next](clone.md)
