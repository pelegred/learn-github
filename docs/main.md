# learn git

## setup

- create github account
- install git
- on terminal configure github to identify you as author

```
// check
git config --global user.name
git config --global user.email

// set
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
```

## basic commnads

- `git init` - creates a .git folder on current directory
- `git status` - to check if any files untracked, or modified
- `git add filename`
- `git add .` - add all changes to staging
- `git commit -m "commit message"`
- `git log` - get a list of commits
- `git checkout <hash>`
- `git checkout master`
- `git branch` - list branches
- `git branch <name>` - create a branch

## basic workflow

- any changes you made to file need to be added
- any new files need to be added
- than, files you added (to staging area) need to be commited
- think of commit as a checkpoint
