# 6.2 Git Clone
This command is used to get a copy of an already existing Git repository. Cloning can be considered as a process of creating an identical copy of Git repository to the local system.
When we clone a repository, all the files are downloaded to local machine, but the remote repository remains unchanged. Editing the local repository and committing changes does not have an impact on the remote version in any way.
However, these changes can be synced with the remote repository anytime the user wants.
Cloning is required for organizations where mulitple people work on the same code base.
By cloning, people can modify the project code or suggest some edits. This helps to achieve greater efficiency in less time with collaboration.
A difference which needs to be clarified here is that `git init` and `git clone` are usually confused with each other.
It's important to understand that `git clone` is dependent on `git init` and creates a copy of repository which already exists.
In other words, for generating `git clone`, we need a repository created with git init.
The most common use of clone is to simply copy the remote respository.
This follows the syntax of `git clone [url]`. This enables the user to take advantage of a full repository on local machine without disturbing the original version.
