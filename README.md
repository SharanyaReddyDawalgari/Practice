# GitHub Command Practice

Welcome to the **GitHub Command Practice** repository! This repository is designed for practicing and learning the fundamental commands used in Git and GitHub. Whether you're a beginner or looking to refresh your skills, this repo provides hands-on experience with essential Git commands and workflows.

## Table of Contents

- [Overview](#overview)
- [Getting Started](#getting-started)
- [GitHub Commands](#github-commands)
- [Branching and Merging](#branching-and-merging)
- [Contributing](#contributing)
- [License](#license)

## Overview

This repository is a sandbox environment where you can:
- Clone repositories
- Create and switch branches
- Commit changes
- Push and pull changes to/from GitHub
- Resolve merge conflicts
- Open pull requests
- Practice rebasing and squashing commits

## Getting Started

To get started, you will need Git installed on your local machine. If you haven't installed Git yet, follow the instructions on [Git's official website](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/github-command-practice.git
   ```

2. Navigate to the repository directory:

   ```bash
   cd github-command-practice
   ```

3. Create your own branch for practice:

   ```bash
   git checkout -b my-practice-branch
   ```

4. Start experimenting with Git commands!

## GitHub Commands

Here are some of the key Git commands you can practice:

- **Clone the repository**:  
  ```bash
  git clone <repo-url>
  ```

- **Check the repository status**:  
  ```bash
  git status
  ```

- **Add changes to the staging area**:  
  ```bash
  git add <file-name>
  ```

- **Commit your changes**:  
  ```bash
  git commit -m "Your commit message"
  ```

- **Push changes to GitHub**:  
  ```bash
  git push origin <branch-name>
  ```

- **Pull the latest changes from GitHub**:  
  ```bash
  git pull
  ```

## Branching and Merging

Practice creating, switching between branches, and merging them:

- **Create a new branch**:  
  ```bash
  git checkout -b <branch-name>
  ```

- **Switch to an existing branch**:  
  ```bash
  git checkout <branch-name>
  ```

- **Merge branches**:  
  ```bash
  git checkout <target-branch>
  git merge <branch-name>
  ```

- **Resolve merge conflicts**: If you encounter conflicts, resolve them manually in your code editor, then:

  ```bash
  git add <file-with-conflict>
  git commit -m "Resolved merge conflict"
  ```

## Contributing

Feel free to make your own contributions and open a pull request. Here’s how you can contribute:

1. Fork this repository.
2. Clone your fork to your local machine.
3. Create a new branch for your feature or bug fix.
4. Commit your changes.
5. Push to your fork and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

