## Installation 

*Download*:  `https://git-scm.com/downloads`.

After download, check your git version to make sure git is there.

'git --version'


##  Setup your identity
git config --global user.name "Your_name"
git config --global user.email you@hotmail.com


## Instruction
Move to your project directory  

```
git status
git add -A
git status
git commit

git remote add origin https://github.com/user/repository.git  
git pull (make sure it is the newest file. Take note: while you making the changes other may push their code into github)
git push
```

#### If you want git to ignore file(not to post to github)

Create .gitignore file

`touch .gitignore`

And add in 
'''
.DS_Store

.project(your ignored file)

*.pyc (ignore all file with pyc extension)
'''

