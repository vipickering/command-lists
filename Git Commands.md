# Git

### Flow
clone -> status -> add files -> commit -> push -> status

## Git Commands

Get the Repo from Git

```
git clone
```

Clone a specific branch. In this case, clone 'dev' branch and make it the working branch.

```
git clone -b dev url.git
```

Check the status

```
git status
```


Add all files (edited, modified and deleted)

```
git add -A
```

Commit all modified files with this message

```
git commit -m "commit message"
```

Push files up

```
git push -u origin master
```

## Heroku Commands

Heroku Create App

```
heroku apps:create my-prototype
```

Heroku Set User name and Password

```
heroku config:set USERNAME=username_here
heroku config:set PASSWORD=password_here
```

Heroku Switch remote app

```
heroku git:remote -a uc-risk
```

Heroku Deploy

```
git push heroku master
```