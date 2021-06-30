# Git and Github Usage

## Git and Github Usage Practice with Blog project

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#Overviwe">Overviwe</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
    </li>
    <li><a href="#Topics-reviewed">Topics reviewed</a></li>
    <li><a href="#Command-list">Command list</a></li>
    <li><a href="#Acquired-skills">Acquired skills</a></li>
  </ol>
</details>



<!-- Overviwe -->
## Overviwe

In this repository you will find a brief summary of what was learned in the [platzi](https://platzi.com/clases/git-github/) course of Git and GitHub.

You will see that it conforms:
* Steps to clone this repository and view what was learned on your own system.
* Main topics seen in the course
* A list of the commands used to create this repository
* Skills acquired at the end of the course



<!-- GETTING STARTED -->
## Getting Started

## Setup

- Fork this repo
- Clone this repo

```shell
$ mkdir git-github-usage-blog
$ cd git-github-usage-blog
$ git clone https://github.com/DiBarrera/git-github-usage-blog.git
```

As you can see here, You will find the following files:

- **blogspot.html:** File created to practice using command lines with git and github
- **css directory:** The css file linked to the HTML
- **Historia.txt:** File created to practice using command lines with git and github

<!-- Topics reviewed -->
## Topics reviewed

The topics seen are about the use of command lines related to git and github.
From a terminal, inside the cloned folder, you can see the commits path

* Inside the directory type:
  ```sh
  $ git log
  ```

You can see the path in commits made

### Topics

- How to commit.
- Stagin files.
- Analyze changes in files.
- Work cycle in git.
- Use of branch and merges.
- "Go back in time" using `rest` and `checkout`.
- Basic workflow with a repository using `git clone`, `git push`, `git fetch`, `git remote` and `git pull`.
- Introduction to branches with `git branch`.
- Merge of branches with `git merge`.
- Using github with commands such as `git remote add origin url`, `git remote`, `git remote -v` and `git pull origin master`.
- Public keys and private keys and their configuration.
- Tags and versions on github with `git tag`.
- Branches and merges with `git branch name-of-the-branch`, `git checkout -b name-of-the-branch` and `git push origin name-of-the-branch`.
- Make a pull request.
- Ignore files with .gitignore.
- README.md
- Git rebase, git statsh, git clean, git cherry-pick, git amend.
- Git grep



<!-- Command list -->
## Command list

## Alias
| Command      | Description                         |
| ------------- | ------------------------------ |
| `alias command-name = "newcommand`     | Configure a command to act with its new alias. |
| `alias treecommits = "git log -all -graph -decorate ---online"`    | Set the command `treecommits` to execute serveral commands. |
| `git config --global alias.name-of-command "command-git"` ó `Ctrl + L`   | Set the command `command-git` globally to execute "`name-of-command`". | 

## Add
| Command      | Description                         |
| ------------- | ------------------------------ |
| `git add .`     | Add all files from the working directory to the stragin area. |
| `git add file-name.ext`    | Add a file or directory from the working directory to the stragin area. | 

## Blame
| Command      | Description                         |
| ------------- | ------------------------------ |
| `git blame -c file-name.ext`     | Shows the user who work in an especific file, displaying time and date betweent atributes. |
| `git blame file-name.ext`    | Shows the user who work in an especific file, displaying time and date. |
| `git blame file-name.ext L initial-number, final-numer -c`    | Shows the user who work in an especific file, detailing time and date of every tabulation between every atribute of the initial number line and the final numer line. | 

## Branch
| Command      | Description                         |
| ------------- | ------------------------------ |
| `git branch -a`     | Displays existing branches inside the git reposiroty and the remote repository. |
| `git branch -d branch-name`    | Deletes the branch branch-name. |
| `git branch -l`    | List all existing branches. |
| `git branch -m branch-name new-branch-name`     | Allows to rename the branch-name to new-branch-name. |
| `git show-branch`     | Displays existing branches and their hisotry. |
| `git show-branch --all`     | Displays all existing branches and their history. |
| `git stash branch branch-name`     | Creates a branch named branch-name from the saving stach and positions you in it. | 

## Checkout
| Command      | Description                         |
| ------------- | ------------------------------ |
| `git checkout -b branch-name`     | Creates a new branch named branch-name and positions you in it. |
| `git checkout hash file-name.ext`    | Allows moving a file file-name.ext back to state according to a commit identified by its hash. |
| `git checkout hash file-name.ext`    | Change the state of a file file-name.ext according to the last master version. |
| `git checkout branch-name`     | Move to from the currently branch to the branch branch-name. | 

## Cherry-pick
| Command      | Description                         |
| ------------- | ------------------------------ |
| `git cherry-pick hash`     | Brings an old commit identified by its hash to the actual branch. | 

## Clean
| Command      | Description                         |
| ------------- | ------------------------------ |
| `git clean --dry-run`     | Simulates duplicate files to be deleted without deleting them. Shows the files to be deleted. |
| `git clean -f`    | Deletes the duplicate files inside the repository. | 

## Clone
| Command      | Description                         |
| ------------- | ------------------------------ |
| `git clone HTTPS/SSH`     | Clone the specified repository. | 

## Commit
| Command      | Description                         |
| ------------- | ------------------------------ |
| `git commit -a`    | Commit the staged snapshot. This will launch a text editor prompting you for a commit message. |
| `git commit -m`    | immediately creates a commit with a passed commit message. |
| `git commit -am`     | This combination immediately creates a commit of all the staged changes and takes an inline commit message. |
| `git commit --ammend -m "messge"`     | This option will modify the last commit. Instead of creating a new commit. |
| `git commit -m "messge"`     | Add the files from the stagin area to the git repository with a description in the "message". | 

## Config
| Command      | Description                         |
| ------------- | ------------------------------ |
| `git config`    | Displays all configurations in Git. |
| `git config --global color.ui true`    | Enable true colors in the UI. |
| `git congit --global core.editor "C:\program-files\software\file.ext"`     | Change the deault vim editor to the selected one
. |
| `git config --global user.name "user-name`     | Set a username to user-name. |
| `git config --global user.email "mail@hosting.com"`     | Set the email to mail@hosting.com. |
| `git config --list`     | Show default git settings. |
| `git config -list -show-origin`     | Shows where the settings are saved. |
| `git config -global alias.new-command-name-git "command-name-git"`     | Set the global command-name-git command to run as new-command-name-git. | 

## Diff
| Command      | Description                         |
| ------------- | ------------------------------ |
| `git diff hash-1 hash-2`    | Shows the changes that have been made between commit 1 identified as hash-1 and commit 2 identified as hash-2. |
| `git diff olf-hash`    | Shows the changes that have been made since the commit identified as old-hash and the current state of the repository. | 

## Fetch
| Command      | Description                         |
| ------------- | ------------------------------ |
| `git fetch`    | Shows the changes that have been made between commit 1 identified as hash-1 and commit 2 identified as hash-2. |
| `git fetch olf-hash`    | Downloads changes from remote repository to the git repository, but does not copy them into the working directory. | 

## Gitk
| Command      | Description                         |
| ------------- | ------------------------------ |
| `gitk`    | Shows the history of the branches in a software. | 

## Grep
| Command      | Description                         |
| ------------- | ------------------------------ |
| `git grep "word"`    | Search inside the repository where the word "word" has been used and show the file. |
| `git grep -c "word"`    | Search inside the repository where the word "word" has been used, show the file and how many times has been used. |
| `git grep -n "word"`    | Search inside the repository where the word "word" has been used, show the file and in which line it is. | 

## Help
| Command      | Description                         |
| ------------- | ------------------------------ |
| `git command-name --help`    | Shows how the command command-name works and its description. | 


## Init
| Command      | Description                         |
| ------------- | ------------------------------ |
| `git init repository-name`    | Create a repository with the name repository-name. | 

## Ssh
| Command      | Description                         |
| ------------- | ------------------------------ |
| `ssh-keygen -t rsa -b 4096 C "mail@host.com"`    | Create a public and private key to automatically connect git with github. |
| `cat ~/.ssh/id_rsa.pub`    | Copy the content of the created key. |
| `eval$(ssh-agent -s)`    | Turn on the keyserver. |
| `ssh-add ~/.ssh/id_rsa`    | Add the private key to the system from the path where it is stored. |
| `ssh-add -L`    | List all active keys. | 

## Log
| Command      | Description                         |
| ------------- | ------------------------------ |
| `git log`    | Shows the history of the commits inside the repository with their respective authors, time and description. |
| `git log --all`    | Shows all the history of the commits inside the repository with their respective authors, time and description. |
| `git log --all --graph --decorate --online`    | Shows the history of the commits of the project in a graphic and orderly way. |
| `git log file-name.ext`    | Shows the history of the commits regarding the file file-name.ext with its respective authors, time and description. |
| `git log -S "word"`    | Search within commits where the word "word" has been used. |
| `git log --stat`    | Shows the specific changes of each file according to their commits. |
| `git log reflog`    | Show the entire history of the repository with its HEAD. |
| `git shortlog`    | Shows all commits made by each contributor. |
| `git shortlog -sn`    | Shows the number of commits made by each contributor. |
| `git shortlog -sn --all`    | Shows the number of commits made by each contributor, including deleted commits. |
| `git shortlog -sn --all --no merges`    | Shows the number of commits made by each contributor, including deleted commits, not including merged branches. | 

## Merge
| Command      | Description                         |
| ------------- | ------------------------------ |
| `git merge`    | Merge the files from the git repository with the ones in the working directory. |
| `git merge branch-name`    | Merge the branch-name branch with the current one, positioning ourselves in the HEAD. |
| `git merge brand-name-2`    | Forces to merge branch-2 with the current one, with the branch in which we are, positioning ourselves in the HEAD. | 

## Pull
| Command      | Description                         |
| ------------- | ------------------------------ |
| `git pull`    | Download changes from a remote repository within a git repository. |
| `git pull origin branch-name`    | Download changes of a branch-name branch of a remote repository and merge them to the current branch, positioning ourselves in the HEAD. |
| `git pull origin branch-name --allow-unrelated-histories`    | Forces the merge of a name-branch branch of a remote repository with the current one, positioning ourselves in the HEAD. | 

## Push
| Command      | Description                         |
| ------------- | ------------------------------ |
| `git push`    | Send the commits to a remote repository. |
| `git push origin :refs/tags/tag-name`    | Remove a tag-name from a remote repository. |
| `git push origin branch-name`    | Send the branch-name to a remote repository. |
| `git push origin branch-name --tags`    | Send the tags of branch-name to a remote repository. |
| `git push origin --tags`    | Send the tags to a remote repository. | 

## Rebase
| Command      | Description                         |
| ------------- | ------------------------------ |
| `git rebase master`    | Receives the commits of the master branch with those of the current one. |
| `git rebase -i master`    | Receives the commits of the master branch with those of the current one, adding according to the order the commits were added interactively. | 

## Reflog
| Command      | Description                         |
| ------------- | ------------------------------ |
| `git reflog`    | Show the entire history of the repository with its HEAD. | 

## Remote
| Command      | Description                         |
| ------------- | ------------------------------ |
| `git remote -v`    | List existing remotes. |
| `git remote add origin url`    | Connect a repository url and give a remote repository source from our local machine in the git repository. |
| `git remote remove origin`    | Remove a connection to a remote repository. |
| `git remote set-url origin url`    | Change the url of a remote repository to the one of origin. | 

## Reset
| Command      | Description                         |
| ------------- | ------------------------------ |
| `git reset`    | Reset current HEAD to the specified state. |
| `git reset --hard`    | Force the reset of a current HEAD to the specified state. |
| `git reset -hard hash`    | Remove all commits that come after a commit specified by its hash, all changes made in the staging area of the working directory are deleted. |
| `git reset HEAD file-name.ext`    | Remove the file-name.ext file from the stagin area and leave it in the working directory. |
| `git reset --mixed hash`    | From a commit identified by its hash, it removes all commits that come after but keeps all changes in the working directory. |
| `git reset --soft hash`    | From a commit identified by its hash, it removes all commits that come after but keeps all changes in the staging area. | 

## Rm
| Command      | Description                         |
| ------------- | ------------------------------ |
| `git rm`    | Remove files or directorys from a git repository. |
| `git rm --cached file-name.ext`    |Remove the file file-name.ext from the staging area, but it keeps it in the working directory. |
| `git rm --force file-name.ext`    | Remove the file file-name.ext from the staging area and from the working directory. | 

## Show
| Command      | Description                         |
| ------------- | ------------------------------ |
| `git show`    | Shows all the historical changes made and where the HEAD is. |
| `git show -branch`    | Shows which are the branches that exist and their history. |
| `git show -branch --all`    | Shows all existing branches and their history. |
| `git show -ref --tags`    | List the existing tags with the respective commits. |
| `git config -list -show-origin`    | Shows where the settings are stored. | 


## Stash
| Command      | Description                         |
| ------------- | ------------------------------ |
| `git stash`    | Save the repository state temporarily. |
| `git stash apply`    | Apply the last saved stash. |
| `git stash apply stash@{#}`    | Apply the selected stash by its id stash@{#}. |
| `git stash branch branch-name`    | Create a branch name-branch from the last saved stash and position us in it. |
| `git stash drop`    | Remove the last stash. |
| `git stash drop stash@{#}`    | Remove a stash identified by its id stash@{#}. |
| `git stash list`    | List all stashes. |
| `git pop`    | Open the last saved stash. | 

## Status
| Command      | Description                         |
| ------------- | ------------------------------ |
| `git status`    | Shows the status of the repository, which branch we are in, which files are in the working directory and which ones are in the staging area. | 


<!-- Acquired skills -->
## Acquired skills

- Keep a Version Control in Projects with Git.
- Merge branches.
- Work in Teams in a Collaborative Way.
- Install Git on your operating system.
