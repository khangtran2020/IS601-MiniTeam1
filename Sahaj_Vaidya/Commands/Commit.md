## 6.4 Commit
The `git commit` is one of the very core functionalities provided by Github.
It captures the history of project's current changes. Commit is considered as 
central building block of a Git project. Commits are created with `git commit` to
save the state of project at a given time. Instead of making changes and
committing it directly to the main repository, users can accumulate the commits
in the local version. \
Common options with `git commit`:\
*`git commit`\
This launches a text editor asking a commit message from the user. 
Once you have entered the message, save the respective file and close the editor to create
the actual commit.\
*`git commit -a` \
This commits the snapshot of all changes made in the current working directory.
It also allows to track the modifications made to the files.\
*`git commit -m "commit message"`\
This is shortcut command that creates a commit with a given commit message.
Generally, by default the `git commit` opens the editor prompting for 
a commit message, but with the help of this command the message is passed in
the command itself thus eliminating the need for editor.



