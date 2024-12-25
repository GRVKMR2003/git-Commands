
# Git Commands

## Overview
This repository contains a collection of useful Git commands for various tasks such as setup, branching, merging, and more. It serves as a quick reference guide for common Git operations.

## Git Commands

### Setup
- **Configure user name and email**
    ```bash
    git config --global user.name "Your Name"
    git config --global user.email "your.email@example.com"
    ```

- **Initialize a new repository**
    ```bash
    git init
    ```

### Basic Commands
- **Clone a repository**
    ```bash
    git clone <repository_url>
    ```

- **Add files to staging area**
    ```bash
    git add <file_name>
    ```

- **Commit changes**
    ```bash
    git commit -m "Commit message"
    ```

- **Push changes to remote repository**
    ```bash
    git push origin <branch_name>
    ```

### Branching and Merging
- **Create a new branch**
    ```bash
    git branch <branch_name>
    ```

- **Switch to a branch**
    ```bash
    git checkout <branch_name>
    ```

- **Merge a branch into the current branch**
    ```bash
    git merge <branch_name>
    ```

### Viewing History
- **Show commit history**
    ```bash
    git log
    ```

- **Show changes between commits**
    ```bash
    git diff <commit_id> <commit_id>
    ```

### Remote Repositories
- **Add a remote repository**
    ```bash
    git remote add origin <repository_url>
    ```

- **Fetch changes from remote repository**
    ```bash
    git fetch origin
    ```

- **Pull changes from remote repository**
    ```bash
    git pull origin <branch_name>
    ```

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

