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

Move to your project directory  
```
git status
git add -A
git status
git commit -m "Your messages lies here"

git remote add origin https://github.com/user/repository.git  
git remote -vv  (make sure it is correct remote repository)
git pull     (make sure it is the newest file. Take note: while you making the changes other may push in their code into github)
git push origin master
```
#### Cloning a remote repo

```
git clone <url> <where to clone>
git clone ../remote_repo.git
git clone https://github.com/user/repository.git .   
```


#### If you want git to ignore file(not to post to github)

Create .gitignore file

`touch .gitignore`

And add in   

```
.DS_Store

.project (your ignored file)

*.pyc (ignore all file with pyc extension)
```





