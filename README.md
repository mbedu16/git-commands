# GIT-commands
Following are the git commands that I came across and did not feel to lazy to write about. If you want to dive deeper than the shallow level of my descriptions, why not click on the command and visit its page to learn a lot more...
## [git clone](https://www.git-scm.com/docs/git-clone)
This is the first command I probably had to use with git. 
### Remote Repository ###
It creates a copy of the remote repository (a directory on git hub) you want to clone in a local working directory of your choice. You will need to provide the url of the remote repository.
> git clone https://github.com/mbedu16/git-commands.git
### Local Repository ###
It is also used to clone from a local repository by providing its path in the local machine instead of the url.
You can use the '-l' or '--local' flag to bypass the GIT transport mechanism.
> git clone --local ~/path/to/repository
## [git log](https://www.git-scm.com/docs/git-log)
For me, this is the next most logical cammand to use after cloning a repository to work with. This logs (or lists) all reachable commits in the repository.
## [git status](https://www.git-scm.com/docs/git-status)
You cloned the repo and you checked all the commits made by your peers. You are now feeling it and start to make your own changes to the programme. git status is your best friend at this stage. It lists all the changed elements of the tree compared with what's already there, giving you insight on when is appropriate to make a commit.
