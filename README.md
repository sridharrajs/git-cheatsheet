# Git-cheatsheet

## Init 

| Command | Description|
| ------- |--------------|
| git init | Initializes the current folder with git  |

## Configuration

| Command | Description |
| ------- |-------------- |
| git config user.name \<your github name\> | will set the name, adding `–global` will set it globally |
| git config user.email \<your email\> | will set the email id, adding `–global` will set it globally |

## Display

| Command | Description |
| ------- |-------------- |
|git config user.name | will display the configured user name of the repo |
|git config user.email | will display the configured email id of the repo |

## Branching

| Command | Description |
| ------- |-------------- |
|git branch | List all branch |
|git branch <branch_name> | Creates a <branch_name> named branch |
|git checkout <branch_name> | Checkout a particular branch |
|git checkout -b <branch_name> | Creates a <branch_name> named branch and checkouts it |
|git branch <branch_name> -d | Delete a local merged branch , `-D` for deleting a unmerged branch |


## Logs

| Command | Description |
|---------|-------------- |
| git log -\<limit\> | No of logs |
| git log --oneline | show logs in single line |


## Videos

[![Webcast • The Basics of Git and GitHu](https://img.youtube.com/vi/U8GBXvdmHT4/maxresdefault.jpg)](https://youtu.be/U8GBXvdmHT4)

## References

**10 tips for better Pull Requests** by Mark Seemann - [Link](https://blog.ploeh.dk/2015/01/15/10-tips-for-better-pull-requests/)
> 1. Make it small
> 2. Do only one thing
> 3. Watch your line width 
> 4. Avoid re-formatting
> 5. Make sure the code builds
> 6. Make sure all tests pass 
> 7. Add tests 
> 8. Document your reasoning
> 9. Write well
> 10. Avoid thrashing

**How to Write a Git Commit Message** by Chris Beams - [Link](https://chris.beams.io/posts/git-commit/)

> 1. Separate subject from body with a blank line
> 2. Limit the subject line to 50 characters
> 3. Capitalize the subject line
> 4. Do not end the subject line with a period
> 5. Use the imperative mood in the subject line
> 6. Wrap the body at 72 characters
> 7. Use the body to explain what and why vs. how
