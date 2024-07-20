## GIT-TUTORIAL
This repository structure and explanation provide a practical way to learn and apply Git commands in a real project. It covers the essential commands and workflows that beginners need to get started with version control using Git.


### Configuration Commands
- **git config --global user.name "Your Name**  
  Sets the name you want attached to your commit transactions.
  
- **git config --global user.email "your_email@example.com**  
  Sets the email you want attached to your commit transactions.

### Basic Commands
- **git init**  
  Initializes a new Git repository in the current directory.

- **git clone <repository_url>**  
  Creates a copy of an existing repository from a URL to your local machine.

- **git status**  
  Displays the state of the working directory and the staging area, showing which changes have been staged, which haven't, and which files aren't being tracked by Git.

- **git add <file>**  
  Stages a specific file, making it ready for the next commit. To stage all changed files, use `git add .`.

- **git commit -m "commit message"**  
  Records the changes made to the repository with a descriptive message.

- **git commit -a -m "commit message"**  
  Stages all tracked files and commits them in one step.

- **`git push`**  
  Uploads your local commits to the remote repository.

- **`git pull`**  
  Fetches and integrates changes from the remote repository to your local repository.

### Branching and Merging
- **`git branch`**  
  Lists all branches in your repository.

- **`git branch <branch_name>`**  
  Creates a new branch with the specified name.

- **`git checkout <branch_name>`**  
  Switches to the specified branch.

- **`git checkout -b <branch_name>`**  
  Creates a new branch and switches to it.

- **`git merge <branch_name>`**  
  Merges the specified branch into the current branch.

### Viewing History
- **`git log`**  
  Shows a list of all the commits in the current branch, starting with the most recent.

- **`git log --oneline`**  
  Displays the commit history in a more concise format.

### Remote Repositories
- **`git remote add <name> <url>`**  
  Adds a new remote repository with the specified name and URL.

- **`git remote -v`**  
  Lists the URLs of the remote repositories you have configured.

- **`git fetch <remote>`**  
  Downloads objects and refs from another repository.

### Undoing Changes
- **`git reset --hard`**  
  Resets the working directory and staging area to the last commit, discarding all changes.

- **`git reset --soft`**  
  Resets the staging area to the last commit, but keeps changes in the working directory.

- **`git revert <commit>`**  
  Creates a new commit that undoes the changes made by the specified commit.

### Advanced Commands
- **`git stash`**  
  Temporarily shelves changes you've made to your working directory.

- **`git stash pop`**  
  Applies the stashed changes to your working directory and removes them from the stash list.

- **`git rebase <branch>`**  
  Reapplies commits on top of another base tip.

### Collaboration Commands
- **`git fork`**  
  Copies a repository on GitHub to your own GitHub account. This is done through the GitHub interface, not a Git command.

- **`git clone <forked_repository_url>`**  
  Clones your forked repository to your local machine.

- **`git pull request`**  
  Submits changes to a project through the GitHub interface by proposing your changes to be reviewed and merged by the project maintainers.

This list includes the most commonly used Git commands that are essential for beginners. Let me know if you need more detailed explanations or examples for any specific command!
