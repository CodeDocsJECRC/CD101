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

#### Git Commands
- `git --version`
- `git clone <url_of_your_remote_repository>`,

  e.g. `git clone https://github.com/CodeDocsJECRC/society`
- `git config --global user.name <user_name>` - configure user name for that repository,

  e.g. `git config --global user.name ShivSoni5`
- `git config --global user.email <user_email>` - configure user email for that repository,

  e.g. `git config --global user.email shivsonic05@gmail.com`
- `git config --list` - list the configured details
- `git add <file_name>`,

  e.g. `git add README.md`
- `git commit -m "First Commit"` - arguement '-m' stands for message
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

- `git init` - Initializing a Git repository for a new or existing project










Some useful resources -
