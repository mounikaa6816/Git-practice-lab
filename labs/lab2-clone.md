# Lab 2: Cloning a Git Repository

## Objective

Learn how to clone a remote GitHub repository to a local computer using Git.

---

## Prerequisites

- Git installed on your computer
- A GitHub account
- An existing GitHub repository
- Internet connection

---

## Theory

**Cloning** is the process of creating a complete local copy of a remote Git repository.

When a repository is cloned, Git downloads:
- Project files
- Complete commit history
- Branches
- Repository configuration

This allows developers to work locally without modifying the remote repository directly.

---

## Command Used

```bash
git clone https://github.com/mounikaa6816/Git-practice-lab.git
```

---

## Workflow

```text
Remote Repository (GitHub)
          │
          │ git clone
          ▼
Local Repository
          │
     Make Changes
          │
      git status
          │
        git add
          │
      git commit
          │
       git push
          ▼
Remote Repository Updated
```

---

## Steps Performed

1. Copied the repository URL from GitHub.
2. Opened Git Bash.
3. Executed the `git clone` command.
4. Downloaded the repository to the local machine.
5. Verified that the repository was cloned successfully.

---

## Key Points

- `git clone` creates a complete local copy of a remote repository.
- The cloned repository includes the entire commit history.
- Developers usually work on the local repository and push changes to GitHub.

---

## Interview Questions

### 1. What is Git Clone?

Git Clone is a command used to create a local copy of a remote Git repository.

---

### 2. Which command is used to clone a repository?

```bash
git clone <repository-url>
```

Example:

```bash
git clone https://github.com/mounikaa6816/Git-practice-lab.git
```

---

### 3. Why do developers clone repositories?

- To work locally
- To make changes safely
- To test applications
- To commit changes
- To push updates back to GitHub

---

### 4. What is the difference between `git clone` and downloading a ZIP file?

| Git Clone | Download ZIP |
|-----------|--------------|
| Downloads the complete repository | Downloads only the current files |
| Includes commit history | No commit history |
| Can push and pull changes | Cannot push or pull changes |
| Connected to Git | Not connected to Git |

---

## Outcome

Successfully cloned the GitHub repository to the local computer and understood the Git workflow.
