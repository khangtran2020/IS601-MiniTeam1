## 6.7 Checkout
In Git terminology, `checkout` is the process of switching between different
versions of the target. The `git checkout` command operates between
three components: files, commit and branches. This command can be used to 
view old commits. Checking out branches is an operation similar to
checking out old commits and files in the working directory
to match it with the selected version of the project. 
The `git checkout` command helps to navigate between branches created by 
`git branch`. Checking out a branch updates the files in the current working
directory to match the version stored in a given branch and it informs
Git to record all the new commits in that branch. The difference between
`git checkout` and `git clone` is that clone works to copy the repository
whereas checkout works to swtich between different versions of the same code
existing on the local system.\
Additionally, the `git checkout` command accepts a -b argument which acts as 
a shortcut method to create a new branch and immediately move to the new
branch. \
`git checkout -b`\
The above command simultaneously creates a new branch and checks it out.
This -b informs that Git to create a new branch before switching to it.
The checkout command allows the user to work on multiple features
of the same repository by switching between them.