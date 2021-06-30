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

** Alias
| Command      | Description                         |
| ------------- | ------------------------------ |
| `alias command-name = "newcommand`     | Configure a command to act with its new alias. |
| `alias treecommits = "git log -all -graph -decorate ---online"`    | Set the command `treecommits` to execute serveral commands. |
| `git config --global alias.name-of-command "command-git"` ó `Ctrl + L`   | Set the command `command-git` globally to execute "`name-of-command`". | 

** Add
| Command      | Description                         |
| ------------- | ------------------------------ |
| `git add .`     | Add all files from the working directory to the stragin area. |
| `git add file-name.ext`    | Add a file or directory from the working directory to the stragin area. | 

** Blame
| Command      | Description                         |
| ------------- | ------------------------------ |
| `git blame -c file-name.ext`     | Shows the user who work in an especific file, displaying time and date betweent atributes. |
| `git blame file-name.ext`    | Shows the user who work in an especific file, displaying time and date. |
| `git blame file-name.ext L initial-number, final-numer -c`    | Shows the user who work in an especific file, detailing time and date of every tabulation between every atribute of the initial number line and the final numer line. | 

** Branch
| Command      | Description                         |
| ------------- | ------------------------------ |
| `git branch -a`     | Displays existing branches inside the git reposiroty and the remote repository. |
| `git branch -d branch-name`    | Deletes the branch branch-name. |
| `git branch -l`    | List all existing branches. |
| `git branch -m branch-name new-branch-name`     | Allows to rename the branch-name to new-branch-name. |
| `git show-branch`     | Displays existing branches and their hisotry. |
| `git show-branch --all`     | Displays all existing branches and their history. |
| `git stash branch branch-name`     | Creates a branch named branch-name from the saving stach and positions you in it. | 

** Checkout
| Command      | Description                         |
| ------------- | ------------------------------ |
| `git checkout -b branch-name`     | Creates a new branch named branch-name and positions you in it. |
| `git checkout hash file-name.ext`    | Allows moving a file file-name.ext back to state according to a commit identified by its hash. |
| `git checkout hash file-name.ext`    | Change the state of a file file-name.ext according to the last master version. |
| `git checkout branch-name`     | Move to from the currently branch to the branch branch-name. | 

** Cherry-pick
| Command      | Description                         |
| ------------- | ------------------------------ |
| `git cherry-pick hash`     | Brings an old commit identified by its hash to the actual branch. | 



<!-- Acquired skills -->
## Acquired skills

- Elementum pulvinar etiam non quam lacus suspendisse faucibus interdum.
- Elementum pulvinar etiam non quam lacus suspendisse faucibus interdum.
- Elementum pulvinar etiam non quam lacus suspendisse faucibus interdum.
- Elementum pulvinar etiam non quam lacus suspendisse faucibus interdum.
- Elementum pulvinar etiam non quam lacus suspendisse faucibus interdum.
- Elementum pulvinar etiam non quam lacus suspendisse faucibus interdum.
- Elementum pulvinar etiam non quam lacus suspendisse faucibus interdum.
- Elementum pulvinar etiam non quam lacus suspendisse faucibus interdum.
- Elementum pulvinar etiam non quam lacus suspendisse faucibus interdum.
