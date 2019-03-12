# Git-cheatsheet

## Init 

| Command | Description
| ------- |--------------
| git init | Initializes the current folder with git  

## Configuration

| Command | Description
| ------- |--------------
| git config user.name \<your github name\> | will set the name, adding `–global` will set it globally
| git config user.email \<your email\> | will set the email id, adding `–global` will set it globally

## Display

| Command | Description
| ------- |--------------
|git config user.name | will display the configured user name of the repo
|git config user.email | will display the configured email id of the repo


## Logs

| Command | Description
|---------|--------------
| git log -\<limit\> | No of logs
| git log --oneline | show logs in single line


## Remote

| Command | Description
|---------|--------------
|git remote add \<shortname\> \<url\> | To add a new remote Git repository
|git remote -v | To shows you the URL that Git has stored for the shortname to be expanded to 
