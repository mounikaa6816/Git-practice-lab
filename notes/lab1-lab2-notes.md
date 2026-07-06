# Git & GitHub Practice Notes

## Lab 1

### 1. What is GitHub?

GitHub is a cloud-based platform that hosts Git repositories. It allows developers to store code, collaborate with teams, track changes, and manage software projects.

**Key Features**
- Stores Git repositories
- Team collaboration
- Version history
- Pull Requests
- GitHub Actions
- Issue tracking


### 2. What is a Repository?

A repository (repo) is a storage location for a project where Git tracks all files and their changes over time.

A repository can contain:
- Source code
- Documents
- Images
- Configuration files
- Project history

Example:

Git-practice-lab/
│── README.md
│── notes/
│── projects/


### 3. What is a README?

A README is the first document in a repository. It explains the purpose of the project, technologies used, setup instructions, and other important information.

A good README usually contains:
- Project title
- Project description
- Features
- Technologies used
- Installation steps
- Author information



### 4. What is a Commit?

A commit is a snapshot of your project at a specific point in time.

Every commit has:
- A unique ID
- A commit message
- Date and time
- Author

Example:


Commit Message:
Add initial README file


Commits help developers track changes and restore previous versions if needed.

# Lab 2

### 5. What is Cloning?

Cloning is the process of copying a GitHub repository from a remote server to your local computer.

Command:

bash
git clone https://github.com/username/Git-practice-lab.git

After cloning, you have a complete local copy of the repository, including its history.



### 6. Why do we use Git Clone?

Developers use `git clone` to:
- Download a project
- Work locally
- Make changes
- Test the application
- Push updates back to GitHub

Workflow:


GitHub Repository
        │
        │ git clone
        ▼
Local Repository
        │
Edit Files
        │
git add
        │
git commit
        │
git push
        ▼
GitHub Repository Updated```



## Summary

| Concept | Description |

| GitHub | Cloud platform for hosting Git repositories |
| Repository | Project folder tracked by Git |
| README | Documentation file for a project |
| Commit | Snapshot of project changes |
| Clone | Copy a repository from GitHub to a local computer |


## Commands Learned
bash
git clone <repository-url>


Example:

bash
git clone https://github.com/mounikaa6816/Git-practice-lab.git



## Interview Questions

1. What is GitHub?
2. What is a repository?
3. What is a README file?
4. What is a commit?
5. What is cloning?
6. Why do developers use `git clone`?
7. What is the difference between Git and GitHub?
8. Can you work on a repository without cloning it?
