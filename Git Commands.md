# Git

### Process

clone -> status -> add files -> commit -> push -> status

## Git Commands

### Get the Repo from Git

```
git clone
```

### Clone a specific branch.
In this case, clone 'dev' branch and make it the working branch.

```
git clone -b dev url.git
```

### Switch branch

```
git branch branchname
```

### checkout branch

```
git checkout -b branchname
```

### Set upstream on first commit

```
git push -u origin branchname
```

### Create the tag

```
git tag archive/<branch_name> <branch_name>
```

### Remove branch and push tag to remote

```
git push --tags origin :<branch_name>
```

### Delete LOCAL branch

Make sure you tag it before you remove it!

```
git branch -D branchname
```


### Check the status

```
git status
```


### Check Git HEAD

```
git fetch
```


### Show available branches

```
git branch
```


### Add all files (edited, modified and deleted)

```
git add -A
```

### Commit all modified files with this message

```
git commit -m "commit message"
```

### Push files up

```
git push -u origin master
```

### Remove a file from history to track

```
git rm --cached -r .filename
```

### Set remote branch to track 

```
git branch --set-upstream-to=origin/branch_name
```

### Prune old remote branches

```
git remote prune origin
```

### Prune local branches that don't have a tracking remote

```
git branch -r | awk '{print $1}' | egrep -v -f /dev/fd/0 <(git branch -vv | grep origin) | awk '{print $1}' | xargs git branch -d
```


## GitK

See all the comments, merges etc

```
gitk --all &
```

## Git Show Remote Branches

```
git remote show origin
```


## Git show all remotes and trackjed

```
git remote show origin
```