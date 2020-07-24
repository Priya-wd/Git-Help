# Git-Help

## Git Installation
**Download Git** 
- Windows OS: [Click here to Download](https://git-scm.com/download/win) & Install It. 
- For Other OS: Visit https://git-scm.com/book/en/v2/Getting-Started-Installing-Git & Install git according to your OS.

**After Installation Check Version**
```
$ git --version
```
**Set Identity**
```
$ git config --global user.name "John Doe"
$ git config --global user.email johndoe@example.com
```
**Check Settings**
```
$ git config --list
```

## How to add a Node.js project to Github using Cloud9/GoormIDE/Any-Cloud-IDE
```
$ git init
$ git add .  (dot)
$ git commit -m "FirstCommit"
$ git status
$ git remote add origin https://github.com/Priya-wd/repo.git
$ git push -u origin master
```

## How to add a Node.js project to Github using VS-Code
```
$ git init
$ git add .  (dot) 
$ git commit -m "FirstCommit"
$ git status
$ git remote add origin https://github.com/Priya-wd/repo.git
$ git pull origin master
$ git push -f origin master
```



