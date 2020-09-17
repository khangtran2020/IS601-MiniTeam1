## 6.8 Push
The `git push` command is used to upload the contents of local repository
to the remotely existing repository. In other words, pushing is how the user
transfers commits from local version to the remote version.
It works similar to `git fetch` but the key difference between both of these
commands is that fetching makes the commit to the local version, but 
push merges the change to the original repository. One thing to be careful
about when using the push command is that it can overwrite the previously 
made changes, hence it should be used with extreme caution to avoid
loss of information.\
How `git push` can be used:
* `git push <name of remote> <name of local branch>`\
This command pushes the specified branch along with the commits
and modifications to the destination repository. 
* `git push <remote version> --force`\
This command works similar to the above command but forces the
push even if it results in a non fast forward merge.
* `git push <remote version> --all`\
This command pushes all the local branches to the specified remote 
repository.\
The most common use of `git push` is to upload local changes to
the central version of the existing repository.