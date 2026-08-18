brief explanation of OSS


diagram comparing ms word and onedrive to git and github

* why ssh
* secrets management
* access control
* automated code auditing

* Setting up a project
  * Initializing git 
    * Through GitHub GUI, from scratch
  * Readme (use GitHub GUI, and introduce markdown syntax)
  * License
  * .gitignore


## [`git`](https://git-scm.com/)

### TL;DR

> `git` is a VCS in the form of a program that keeps track of changes made to all files in a given folder. It is primarily used to access past versions of files or combine different versions of them that have had changes made in parallel.

### History lesson

* Open source software originally written by Linus Torvalds
* Designed as a version control solution for the Linux kernel
* Widely adopted by people who code for a living

### Interface

`git` is intended to be used from the command line, but point-and-click-style (and adjacent) clients also exist. For example:

* [GitHub Desktop](https://github.com/apps/desktop)
* [RStudio (!)](https://docs.posit.co/ide/user/ide/guide/tools/version-control.html#getting-started)

## [GitHub](https://docs.github.com/en)

### TL;DR

> GitHub is a cloud provider for storing and looking at code that you are managing with `git`.

### History lesson

* Originally its own company, now owned by Microsoft 
* Known for hosting the code for many open source projects

### Features

GitHub has visual tools for:

* Collaboration
* Project management
* User support
* Building runnable software from code

### Alternatives

There are other `git` cloud providers out there that are less ... vertically-integrated. Some of them are even open source projects themselves!

* [GitLab](https://docs.gitlab.com/)
* [Codeberg](https://docs.codeberg.org/)

These platforms often have [instructions](https://docs.gitlab.com/user/project/import/github/) for [moving your code over](https://docs.codeberg.org/advanced/migrating-repos/) from GitHub.



## GitHub setup

### New repository

* Click on your profile icon in the top right
* Select `Repositories` from the dropdown
* Click the `New` button near the top right

### Existing repository

* Navigate to the repository
* Click the `Fork` button near the top right
* On the next page, click the `Create fork` button
