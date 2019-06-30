## What is Git

Git is a version control system thatGit is an example of a distributed version control system (DVCS) commonly used for open source and commercial software development.
It tracks the history of changes as people and teams collaborate on projects together. Without version control, team members are subject to redundant tasks, slower timelines, and multiple copies of a single project.
Git allow developers to work in every time zone, sees all the entire timeline of their changes, decisions, and progression of any project in one place. 
As the project evolves, teams can run tests, fix bugs, and contribute new code with the confidence that any version can be recovered at any time. Developers can review project history to find out:

* Which changes were made?
* Who made the changes?
* When were the changes made?
* Why were changes needed?
 
## What’s a repository?
A repository, or Git project, encompasses the entire collection of files and folders associated 
with a project, along with each file’s revision history. The file history appears as snapshots in time called
commits, and the commits exist as a linked-list relationship, and can be organized into multiple lines of development called branches.
 
 
## Installation 

*Download*:  `https://git-scm.com/downloads`.

After download, check your git version to make sure git is there.

`git --version`

## Understanding Git  
Git has three stages.  

<img src="http://i.stack.imgur.com/zLTpo.png" height=" 300px" width="300px" />

##  Setup your identity
Other developers will know who makes the changes by seeing the log file 'git log'

```
git config --global user.name "Your_name"  
git config --global user.email you@hotmail.com
```

## Instruction

Make your project directory
```
git init
```

Move to your project directory  
```
### Check status of the git
git status     
### Add the file to staging area
git add -A
### Check status after adding the file. Make sure the file is there
git status

### Must create message
git commit -m "Your messages lies here"

git remote add origin https://github.com/user/repository.git  

### make sure it is correct remote repository
git remote -vv  

### (make sure it is the newest file. Take note: while you making the changes other may push in their code into github)
git pull     
### commit to git repository
git push origin master
```
#### Cloning a remote repo

```
git clone <url> <where to clone>
git clone ../remote_repo.git
git clone https://github.com/user/repository.git .   
```

Click here_ for more:
.. _here: https://git-scm.com/docs 

#### If you want git to ignore file(not to post to github)

Create .gitignore file

`touch .gitignore`

And add in   

```
.DS_Store

.project (your ignored file)

*.pyc (ignore all file with pyc extension)
```





