## 6.1 Repository
A Git repository provides a virtual storage for the project. It allows the 
user to work on different versions of the same code.
To create a new repo, you'll use the `git init` command. This
`git init` is a one-time command you use during the initial setup of a new repo. Executing this command will create a new .git subdirectory in your current working directory. 
This will also create a new master branch. 

Pointing `git init` to an existing project directory 
will execute the same initialization setup, 
but scoped to that project directory.
The git init command creates a new Git repository. 
It can be used to convert an existing, unversioned project to a Git repository or initialize a new, empty repository. Most other Git commands are not available outside of an initialized repository, so this is usually the first command you'll run in a new project.

Executing `git init` creates a .git subdirectory in 
the current working directory, 
which contains all of the necessary Git metadata 
for the new repository. This metadata includes 
subdirectories for objects, refs, and template files.