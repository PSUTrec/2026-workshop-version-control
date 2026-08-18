* config
* clone
* make local changes with vs code

* git commands
  * status
  * diff
  * add
  * commit
  * log
  * reflog


## `git` vocabulary

* Repository: a folder that `git` is keeping track of
  * Root: the base folder of the repository
* Commit: a snapshot of all the files in the repository at a given time
* Branch: a name (e.g. `main`) referring to a commit
  * Default branch: the branch that is considered "canonical"
* Fork: a copy of an entire repository (including e.g. past commits)
* Remote: a URL pointing to another copy of the repository
  * Upstream: the "canonical" copy of the repository

### Download code (1/2)

> This approach requires that you have [set up an SSH key for GitHub](https://docs.github.com/en/authentication/connecting-to-github-with-ssh).

* Navigate to the repository
* Click the green `Code` button near the top right
* switch to the `SSH` tab
* Copy the link


## Command line setup

### Configure `git`

```bash
git config --global user.name "Firstname Lastname"
# Should match the email you used when signing up for GitHub
git config --global user.email "email@example.com"
```

### Download code (2/2)

```bash
# cd to the folder where you would like to put your copy of the repository (as a subfolder)
cd my-repositories
# Creates a subfolder with your copy of the repository with the same name as the repository
git clone git@github.com:my-username/intro-r-2026
```

### Configure upstream

```bash
# Registers the main repository locally under the name "upstream"
git remote add upstream git@github.com:PSUTrec/intro-r-2026
# Gets a local copy of the main repository's branches (doesn't automatically reconcile your changes with them)
git fetch upstream
```

## Updating the code

### Inspecting changes

```bash
# What files have changed since the last commit
git status
# What changes have been made within those files
git diff
# If you have already run git add on some files, they will only show up as "staged"
git diff --staged
```

### Looking at history

```bash
# Lists commit messages and authors
git log
# Adds in a diff-like view of the changes for each commit
git log -p
# Commit name and author name that last modified each line of the file
git blame my-file
```

### Switching to a branch

```bash
# Creates a new branch that will be kept separate from the default one
git switch -c my-branch
# Switches to an existing branch
git switch main
```

### Creating a commit

```bash
# Adds this entire folder to the list of things to commit
git add .
# Adds a single file
git add my-file
# Saves a snapshot of all added files as they currently are
git commit -m "a short description of the changes"
```

### Syncing your work

```bash
# Switch to whatever branch your work is on
git switch my-branch
# Get the latest changes from the main repository
git fetch upstream main
# Combine your code with the code in the main repository automatically
git merge upstream/main
# Sends a copy of your current branch to your fork on GitHub
git push origin HEAD
```

> If the output of `git merge` tells you there are merge conflicts, you can resolve them by editing the files with a text editor and reconciling the differences yourself
