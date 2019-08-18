# Git-journal


## README.md

Write your README as the first thing in your project. 

**Reference**

* [Readme Driven Development](http://tom.preston-werner.com/2010/08/23/readme-driven-development.html) by Tom Preston-Werner
* [Documentation Driven Development](https://blog.izs.me/2017/06/documentation-driven-development) by Isaac Z. Schlueter


## Init 

| Command | Description|
| ------- |--------------|
| git init | Initializes the current folder with git  |

## Configuration

| Command | Description |
| ------- |-------------- |
| git config user.name \<your github name\> | will set the name, adding `–global` will set it globally |
| git config user.email \<your email\> | will set the email id, adding `–global` will set it globally |
| git config user.name | will display the configured user name of the repo |
| git config user.email | will display the configured email id of the repo |

## Add/Remove/Stage file

| Command | Description |
| ------- |-------------- |
| git add <file_name_with_relative_path>| Adding a single file, `.` for adding all the staged files |



## Branching

| Command | Description |
| ------- |-------------- |
| git branch | List all branch, `-a` for including remote branches in the listing |
| git branch <branch_name> | Creates a <branch_name> named branch |
| git checkout <branch_name> | Checks out the <branch_name> branch |
| git checkout -b <branch_name> | Creates a <branch_name> named branch and checkouts it |
| git branch <branch_name> -d | Delete a local merged branch , `-D` for deleting a unmerged branch |
| git fetch && git checkout <branch_name>| If it is same origin, else fetch `remote` and then checkout|


## Logs

| Command | Description |
|---------|-------------- |
| git log -\<limit\> [branch_name] | `limit` = No of logs. `branch_name`(may be remote or local branch) is optional. Without `branch_name` it will show the latest commit of current branch. |
| git log --oneline | show logs in single line |