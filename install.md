# Git Installation Guide
## How to install Git on any OS

Git can be installed on the most common operating systems like Windows, Mac, and Linux. In fact, Git comes installed by default on most Mac and Linux machines!

### Checking for Git
To see if you already have Git installed, open up your terminal application.

- If you're on a Mac, look for a command prompt application called "Terminal".
- If you're on a Windows machine, open the windows command prompt or "Git Bash".

Once you've opened your terminal application, type `git version`. The output will either tell you which version of Git is installed, or it will alert you that git is an unknown command. If it's an unknown command, read further and find out how to install Git.

### Install Git Using GitHub Desktop
Installing GitHub Desktop will also install the latest version of Git if you don't already have it. With GitHub Desktop, you get a command line version of Git with a robust GUI. Regardless of if you have Git installed or not, GitHub Desktop offers a simple collaboration tool for Git. You can learn more [here](https://desktop.github.com/).

### Install Git on Windows
1. Navigate to the latest [Git for Windows installer](https://git-scm.com/download/win) and download the latest version.
2. Once the installer has started, follow the instructions as provided in the Git Setup wizard screen until the installation is complete.
3. Open the windows command prompt (or Git Bash if you selected not to use the standard Git Windows Command Prompt during the Git installation).
4. Type `git version` to verify Git was installed.

### Install Git on Mac
Most versions of MacOS will already have Git installed, and you can activate it through the terminal with `git version`. However, if you don't have Git installed for whatever reason, you can install the latest version of Git using one of several popular methods as listed below:

#### Install Git From an Installer
1. Navigate to the latest [macOS Git Installer](https://git-scm.com/download/mac) and download the latest version.
2. Once the installer has started, follow the instructions as provided until the installation is complete.
3. Open the command prompt "terminal" and type `git version` to verify Git was installed.

#### Install Git from Homebrew
Homebrew is a popular package manager for macOS. If you already have Homebrew installed, you can follow the below steps to install Git:
1. Open up a terminal window and install Git using the following command: `brew install git`.
2. Once the command output has completed, you can verify the installation by typing: `git version`.

### Install Git on Linux
Fun fact: Git was originally developed to version the Linux operating system! So, it only makes sense that it is easy to configure to run on Linux.

You can install Git on Linux through the package management tool that comes with your distribution.

#### Debian/Ubuntu
Git packages are available using apt.
1. It's a good idea to make sure you're running the latest version. To do so, Navigate to your command prompt shell and run the following command to make sure everything is up-to-date: `sudo apt-get update`.
2. To install Git, run the following command: `sudo apt-get install git-all`.
3. Once the command output has completed, you can verify the installation by typing: `git version`.

#### Fedora
Git packages are available using dnf.
1. To install Git, navigate to your command prompt shell and run the following command: `sudo dnf install git-all`.
2. Once the command output has completed, you can verify the installation by typing: `git version`.

Note: You can download the proper Git versions and read more about how to install on specific Linux systems, like installing Git on Ubuntu or Fedora, in [git-scm's documentation](https://git-scm.com/doc).

[Previous](README.md) | [Next](config.md)
