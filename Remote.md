# Remote

## Config

| Command | Description | Example |
|---------|--------------|------|
|git remote add \<shortname\> \<url\> | To add a new remote Git repository | git remote add github2 git@github.com:sridharrajs/git-cheatsheet.git|
|git remote -v | To shows you the URL that Git has stored for the shortname to be expanded to |

## Branching from a remote repo

First add a remote repo to the list of sources

    git fetch <remote>

Then checkout 

    git checkout -t <remote>/branch    