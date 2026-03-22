# Git & Github Assignment

## 1. What is Version Control?
Version control is a system that helps you track changes made to files (especially code) over time.  
It allows you to:
- See what changes were made
- Go back to previous versions
- Work with others without overwriting each other’s work

Version control is like a history tracker for your project.



## 2. Difference Between Git and GitHub

- Git is a version control system, meaning it is a tool installed on your computer that helps you track changes in your files, manage different versions of your project, and work on code even without an internet connection. It keeps a complete history of your work and allows you to revert to earlier versions when needed.

- GitHub is an online platform that hosts Git repositories in the cloud. It allows you to store your projects online, share them with others, and collaborate with people from anywhere in the world

Git handles the actual tracking of changes, GitHub provides a space for teamwork, backup, and collaboration

## 3. 3 GitHub Alternatives
- GitLab  
- Bitbucket  
- SourceForge  


## 4. Difference Between `git fetch` and `git pull`

### `git fetch`
- Downloads changes from a remote repository
- Does NOT merge them into your current branch


### `git pull`
- Downloads changes AND merges them into your current branch



## 5. Git Rebase 

Rebase means moving your work to start on top of another branch.  
It keeps your project history clean and straight.

Instead of merging, it “replays” your changes on top of the latest code.

### Command:

git rebase <branch-name>

## 6. Git cherry-pick
Cherry-pick means taking a specific commit from one branch and applying it to another branch.

### command:
 git cherry-pick <commit-hash>