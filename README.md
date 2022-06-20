### Configure Email and Name in system

```
git config --global user.email "your@email.com"
git config --global user.name "Your Name"
```

### Initialize empty git repository (to be run inside project folder)

```
git init
```

### Check status of git repo

```
git status
```

## Usual Workflow

### Make changes relative to project directory and add to staging

```
git add --all
```

### Make a commit for all changes in staging

```
git commit -m "Your message here"
```

## Working with Remote

### To add a remote repository

```
git remote add origin [url_of_remote_repository]
```
### To remove remote repository

```
git remote remove origin
```

### Push changes to remote repository

```
git push origin master
```

