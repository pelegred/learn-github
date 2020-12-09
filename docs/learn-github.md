# learn git

## setup

- create github account

## basic workflow

- make a new repo on github
- add a remote (repo url) to project
- push to github

## add a remote

- remote is a label for url
- tells git that this is a place to push to or pull from
- origin - a standard name for the remote

```
git remote add origin https://github.com/pelegred/learn-github.git
```

- optional step to rename master branch to main branch

```
git branch -M main
```

- the final step is to push the code

```
git push -u origin main
```
