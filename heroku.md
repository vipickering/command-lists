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

### Heroku Destroy App

```
heroku apps:destroy --app example
```