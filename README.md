# git-collaboration-dan
Git collaboration notes

- `git clone <utl>`: downloads the repository from the web to your local computer
    - make sure you don't nest this command into another repository
    - just like `git init`, only do this once per repo

- `git branch <branch_name>`: create a new branch where HEAD is
    - `git branch -a`: list all branches your local computer knows of
- `git switch <branch_name>`: move to branch
    - `git checkout <branch_name>`: the pre-august 2019 way

- `git switch -c <branch_name>`: create amd move to branch in 1 step
    - `git chaeckout -b <branch_name>`

- `git log --oneline --graph --all --decorate`: shows you your git history tree
    - you can look up how to set this as an git alias
	
- `git fetch --prune`: clean your git history and remove references from remote that no longer exists

- `git branch -d <branch_name>`: removes branch fromyour local computer

- Pull request: when you push a branch to the remote, and merge the branch in the online interface
