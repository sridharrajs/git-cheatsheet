## Branching

| Command | Description |
| ------- |-------------- |
| git branch | List all branch, `-a` for including remote branches in the listing |
| git branch <branch_name> | Creates a <branch_name> named branch |
| git checkout <branch_name> | Checks out the <branch_name> branch |
| git checkout -b <branch_name> | Creates a <branch_name> named branch and checkouts it |
| git branch <branch_name> -d | Delete a local merged branch , `-D` for deleting a unmerged branch |
| git fetch && git checkout <branch_name>| If it is same origin, else fetch `remote` and then checkout|
