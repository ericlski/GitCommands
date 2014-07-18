# Git Commands

### Creating a repository online for the 1st time
``` sh
# navigated into the folder I wanted to put on Github
$ touch README.md 
$ git init # initialize the git repository locally
$ git add README.md # adds everything changed from local to staging
$ git commit -m "first commit" # commits everything in staging to be ready to be pushed to Github
$ git remote add origin https://github.com/ericlski/GitCommands.git
% git push -u origin master
# put in username and password
```


### When adding to repository with changes
``` sh
$ git add .
$ git add -u # when you have deleted a local file you want to remove from your repo
$ git commit -m "what has changed"
$ git push
# put in username and password
```

### No more username and password input for every push
``` sh
$ git remote set-url origin git@github.com:yourUsername/yourReponame.git
```

### Working together from perspective of person without main repo
``` sh
# fork repo you want to work on
$ git clone https://github.com/yourUsername/yourReponame.git
# add changes to the forked repo
# make a pull request
```

### Want to remove a file from online github repo but keep it locally
``` sh
$ git rm --cached localFileName
# add localFileName to .gitignore file and then commit these changes
```
