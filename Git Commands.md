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

### Check the status

```
git status
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
git branch --set-upstream-to=origin/branch_name branch_name
```

## Git Flow

### Install Git Flow

```
_brew install git-flow
```

### Setup Git Flow

```
git flow init
```

### Create a feature branch using Git Flow

```
git flow feature start BRANCHNAME
```

### Publish branch using Git Flow

```
git flow feature publish BRANCHNAME
```

## Heroku Commands

### Heroku Create App

```
heroku apps:create my-prototype
```

### Heroku Set User name and Password

```
heroku config:set USERNAME=username_here
heroku config:set PASSWORD=password_here
```

### Heroku Switch remote app

```
heroku git:remote -a uc-risk
```

### Heroku Deploy

```
git push heroku master
```