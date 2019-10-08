# Commit
Standard 4 steps to commit changes: `status -> add -> commit -> push`

## Verifying changes in working directory
`git status`

Eg:

    git status

## Add changes to Staging Area 

`git add <options>`

Eg:    

    git add .
    git add *.java

[Documentation](https://git-scm.com/docs/git-add)

## Commit changes
`git commit <options>`

Eg:

    git commit -m "commit message here"
    git commit -a 

[Documentation](https://git-scm.com/docs/git-commit)

## Publish local changes to remote
`git push <options>`

Eg:

    git push
    git push origin
    git push origin :
    git push -u origin master

[Documentation](https://git-scm.com/docs/git-push)


### Changes to tracked files
`git diff <options>`

Eg:

    git diff


[Documentation](https://git-scm.com/docs/git-diff)

### Good Practices

**How to Write a Git Commit Message** by Chris Beams - [Link](https://chris.beams.io/posts/git-commit/)

> 1. Separate subject from body with a blank line
> 2. Limit the subject line to 50 characters
> 3. Capitalize the subject line
> 4. Do not end the subject line with a period
> 5. Use the imperative mood in the subject line
> 6. Wrap the body at 72 characters
> 7. Use the body to explain what and why vs. how