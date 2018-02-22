# Getting started with Git / Github

## Instructor - Shiv Soni
## Venue - LT4
## Time & Date - 12:45 - 2:00 22-02-2018

### Important Links & Commands to get you started with **GIT**
#### Debian (Ubuntu)
`sudo apt-get update` - update dependencies of Ubuntu

`sudo apt-get install git` - install git
#### RPM (Redhat, Fedora)
`yum install git` - install git
#### Windows
Download Git Bash from [GitForWindows](https://gitforwindows.org)

#### Setting up a repository
Cloning an existing Git repo -
- `git clone <url_of_your_remote_repository>`,

  e.g. `git clone https://github.com/CodeDocsJECRC/society`

Configuring Git repo for remote collaboration -
- `git config --global user.name <user_name>` - configure user name for that repository,

  e.g. `git config --global user.name ShivSoni5`
- `git config --global user.email <user_email>` - configure user email for that repository,

  e.g. `git config --global user.email shivsonic05@gmail.com`
- `git config --list` - list the configured details

#### Initializing a Git repository for a new or existing project -
- `git init` - Initialize the current directory as git directory
- `git remote add <remote_repo_name> <remote_repo_URL>`,

  e.g. `git remote add origin https://github.com/CodeDocsJECRC/society`
- `git add .`
- `git commit -m "message"`
- `git push -u <remote_repo_name> <branch_name>`,

  e.g. `git push -u origin master`

#### Common Git version control commands
- `git add <file_name>` - File will be tracked

  e.g. `git add README.md`
- `git commit -m "First Commit"` - tracked file will be committed
- `git push origin <branch_name>` - pushing commits to server repository,

  e.g. `git push origin bug`
- `git branch <branch_name>` - Creating new branch,

  e.g. `git branch bug`
- `git checkout <branch_name>` - Switch Branch,

  e.g. `git checkout bug`
- `git checkout -b <branch_name>` - Creating and switching to new branch
- `git merge <branch_name>` ,

  e.g. `git merge bug` - merging bug into master branch (present by default)
- `git branch -d branch_name` - Deleting a branch,

  e.g. `git branch -d bug`
- `git log` - provides commit ID and history
- `git reset --hard old_ID` - Head to any previous commit
- `git diff old_ID new_ID` - To view the changes you make in a file

### Some useful resources
#### Documentations and Tutorials
- [Learn Git](https://www.atlassian.com/git/tutorials/learn-git-with-bitbucket-cloud)
- [Try Git](https://try.github.io/levels/1/challenges/1)
- [Git-Book](https://git-scm.com/book/en/v2)

#### Video Tutorials & Playlists
- [thenewboston](https://www.youtube.com/playlist?list=PL6gx4Cwl9DGAKWClAD_iKpNC0bGHxGhcx)
- [cs50](https://www.youtube.com/watch?v=MJUJ4wbFm_A)
