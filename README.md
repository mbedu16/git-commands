# GIT-commands
## [git clone](https://www.git-scm.com/docs/git-clone)
This is the first command I probably had to use with git. 
### Remote Repository ###
It creates a copy of the remote repository (a directory on git hub) you want to clone in a local working directory of your choice. You will need to provide the url of the remote repository.
> git clone https://github.com/mbedu16/git-commands.git
### Local Repository ###
It is also used to clone from a local repository by providing its path in the local machine instead of the url.
You can use the '-l' or '--local' flag to bypass the GIT transport mechanism.
> git clone --local ~/path/to/repository
