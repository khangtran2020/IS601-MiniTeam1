## 6.6 Merge
The `git merge` command allows you to take the independent versions
of the project and integrate these versions into the main branch.
This `git merge` will combine multiple commit sequences into one
single unified history. One of the very frequent uses of `git merge` is to
combine two branches together. Before using `git merge` make sure that
the correct local branch is checked out. Once this is done, perform the merge by
specifying the following commands:
* `git checkout localbranch`
* `git merge feature`

Conflicts often occur when using the merge command. Conflicts generally 
arise when two users have updated the same line in a file or if one user
deleted a file while another was editing it. In such cases, it is not
possible for Git to automatically determine what is correct. 
So it will tag the file as being conflicted pause the merging process.
`git merge` will implicitly determine a merge strategy unless specified.
The `git merge` command can be used with a -s option. This can be
appended with the name of the corresponding strategy.

Merge commits are unique from the usual commits because they have two
parent commits. When creating a merge commit, Git will attempt to 
merge the separate histories for you. If it comes across some data which 
was changed in both the histories, it will be unable to combine them.
In such a case, merge conflict arises and requires intervention
from the user to resolve it.

When doing `git merge`, Git will find a common base commit and will
create a new 'merge commit' that combines the changes of
each of the separate commits.