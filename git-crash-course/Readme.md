** Git Hidden Folder

There is a hidden folder called `.git` which tells you that are project is a git repo.

If we wanted to create a new repo in a new project we created the folder and initialised that repo using `git init`


```sh
mkdir /workspaces/tmp/new-project
cd /workspaces/tmp/new-directory
git init
touch Readme.md
code Readme.
git status
git add Readme.md
** Makes changes to Readme.md
git commit -m "add Readme file"
```

** Cloning 

We can clone three ways HTTPS, SSH and Github CLI

Since we are using GitHub Codespaces we'll create a temporary directory in our workspace

```sh
mkdir /workspaces/tmp
cd /workspaces/tmp
```


** HTPPS

```sh
git clone https://github.com/ooroosta/TEST.git
cd TEST
```

** Commits
When we want to commit code we can run git commit which will open up the commit edit message in the editor of choice.

```sh
git commit
```
Set the global editor
```sh
git config --global core.editor emacs


** Branches

** Remotes

** Stashing

** Merging

** Add

When we want to stage changes that will be included in the commit. We can use the . to add all possible files.

** Reset

Reset allows you to move staged changed back to unstaged. Usefull to remove files not to be commited

```sh
git add .
git reset
```
** git reset will revert a git add .

** Status
Git status shows you what files will or will not be commited

```sh
git status
```

** Git Config file

The git config file is what stores your global configuration for git such as email, name, editor, and more.

```sh
git config --list
```