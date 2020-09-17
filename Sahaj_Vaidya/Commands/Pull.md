## 6.9 Pull
The `git pull` command is used to fetch the content from the remote 
repository and download it to the local system to update the
version existing on the local. Actually, `git pull` is a combination of two
different commands, `git fetch` and `git merge`. In the initial phase
pull will execute fetch to the local branch. Once that is done, pull
will start the execution of the merge command. Pull requests are features
that help a user to perform collaboration on the same project.
To put in simple words, pull requests are a mechanism for the user to notify 
other users that they have modified a feature. This lets everybody know
that they can review the edited code and merge it into the master branch.
Common usage options:
* `git pull <remote branch`\
This command fetches the specified remote copy merges into the 
local copy. This is same as doing `git fetch` followed by 
`git merge`.
* `git pull --no-commit <remote branch`\
Similar to the above command, it gets the content from the remote copy
but does not create a new commit.
* `git pull --rebase <remote branch`\
It uses `git merge` to integrate the remote branch with the local one

Thus, `git pull` is a convenient way to local version of the project
with the original repository.