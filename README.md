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
$ git commit -m "what has changed"
$ git push
# put in username and password
```