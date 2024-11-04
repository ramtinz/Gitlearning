# Mini Guide to Git

## Basic Git Workflow

Git is the industry-standard version control system for web developers. Use the following commands to manage your projects:

| Command               | Description                                                                                  |
|----------------------|----------------------------------------------------------------------------------------------|
| `git init`           | Creates a new Git repository.                                                                |
| `git status`         | Inspects the contents of the working directory and staging area.                             |
| `git add`            | Adds files from the working directory to the staging area.                                  |
| `git diff`           | Shows the difference between the working directory and the staging area.                    |
| `git commit`         | Permanently stores file changes from the staging area in the repository.                   |
| `git log`            | Shows a list of all previous commits.                                                       |

---

## How to Backtrack

You can undo changes in your Git project using these commands:

| Command                     | Description                                                              |
|----------------------------|--------------------------------------------------------------------------|
| `git checkout HEAD filename` | Discards changes in the working directory.                             |
| `git reset HEAD filename`   | Unstages file changes in the staging area.                             |
| `git reset commit_SHA`      | Resets to a previous commit in your commit history.                    |

You can also add multiple files to the staging area with a single command:

```bash
git add filename_1 filename_2
```
## Git Branching

Git branching allows users to experiment with different versions of a project. Use the following commands in the Git branch workflow:

- `git branch`: Lists all branches in a Git project.
- `git branch branch_name`: Creates a new branch.
- `git checkout branch_name`: Switches from one branch to another.
- `git merge branch_name`: Joins file changes from one branch to another.
- `git branch -d branch_name`: Deletes the specified branch.

---

## Git Teamwork

Collaboration on Git projects is streamlined through the use of remotes, which are Git repositories located outside your local project folder. Key commands for collaboration include:

- `git clone`: Creates a local copy of a remote repository.
- `git remote -v`: Lists a Git project’s remotes.
- `git fetch`: Fetches work from the remote into the local copy.
- `git merge origin/master`: Merges changes from `origin/master` into your local branch.
- `git push origin <branch_name>`: Pushes a local branch to the origin remote.

Git projects are commonly managed on **GitHub**, which allows you to access your projects from anywhere in the world.
