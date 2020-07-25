# Git-Help

## Git Installation
**Download Git** 
- Windows OS: [Click here to Download](https://git-scm.com/download/win) & Install It. 
- For Other OS: Visit https://git-scm.com/book/en/v2/Getting-Started-Installing-Git & Install git according to your OS.

> After completing installation process open Git-CMD and do following One-Time Settings

**Check Version**
```
$ git --version
```
**Set Identity**
```
$ git config --global user.name "John Doe"
$ git config --global user.email johndoe@example.com
```
**Set VS-Code as Core Editor**
> Make sure you can run `$ code --help` from the command line and you get help
> If not, then & then only run following command
```
$ git config --global core.editor "code --wait"
```
**Check Settings**
```
$ git config --list
```
## How to add a Node.js project to Github using VS-Code
> Open correct `project folder` & run following commands from vs-code
```
$ git init
$ git add .  (dot) 
$ git commit -m "FirstCommit"
$ git status
$ git remote add origin https://github.com/Priya-wd/repo.git
$ git pull origin master
$ git push -f origin master
```

## How to add a Node.js project to Github using Cloud9/GoormIDE/Any-Cloud-IDE
> Make sure yo are in correct `project directory` & run following commands
```
$ git init
$ git add .  (dot)
$ git commit -m "FirstCommit"
$ git status
$ git remote add origin https://github.com/Priya-wd/repo.git
$ git push -u origin master
```

## dotenv (.env)
> Make sure you have installed dotenv package. 
```
npm install dotenv
```
>  Create a file as .env & add environment variables. e.g:
```
DB_USER=demo123
DB_URL=mongodb://localhost:27017/dbname
```

## .gitignore
> Create a file .gitignore & add all files & folders which you want to hided from others to it. For e.g:
```
node_mdules/
.env
package-lock.json
```
> After saving .ignore file run following commands
```
git rm -rf --cached .
git add .
```
> This removes all files from the repository and adds them back (this time respecting the rules in your .gitignore).

## Git Remote
```
git remote
git remote [-v | --verbose]
git remote add [-t <branch>] [-m <master>] [-f] [--[no-]tags] [--mirror=<fetch|push>] <name> <url>
git remote rename <old> <new>
git remote remove <name>
git remote set-head <name> (-a | --auto | -d | --delete | <branch>)
git remote set-branches [--add] <name> <branch>…​
git remote get-url [--push] [--all] <name>
git remote set-url [--push] <name> <newurl> [<oldurl>]
git remote set-url --add [--push] <name> <newurl>
git remote set-url --delete [--push] <name> <url>
git remote [-v | --verbose] show [-n] <name>…​
git remote prune [-n | --dry-run] <name>…​
git remote [-v | --verbose] update [-p | --prune] [(<group> | <remote>)…​]
```


