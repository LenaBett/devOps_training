# DevOps Repository

## Table  of Contents

[Setting-up](#setting-up)
- [Initializing a local repository](#initializing-a-local-repository )


### Setting-up
#### Initializing a local repository 


- Create a folder (directory) which you wish to control with git
- Open the folder and Open GitBash from the folder.
- Use '$ git init' to create the new repository
- Configure your credentials using the '$ git --global' command as shown:
-       $ git config --global user.name "John Doe"
-       $ git config --global user.email johndoe@example.com
#### Linking the local repository to a remote repository
- Open the remote repository on the Github website
- Copy the repository link e.g 
-       (http) "https://github.com/example/my_project.git"
-       (SSH) "git@github.com:example/my_project.git"
- Use the 'git remote add origin' command as shown:
-        $ git remote add origin git@github.com:example/my_project.git
