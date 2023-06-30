# Git vs Github
- Git
It's a particular implementation of the versioning control system (2005) as a way of managing the Linux kernel. Git manages the evolution of a set of file (repository)
- Github
It's an online hub for hosting Git repositories and provides GUI software for usign Git.

## Git
Git takes snapshots of your files that record the files in your repository look like at any given point in time. <br>
Youd decide when to take a snapshot and of what files, this is known as a commit. <br>
Each commit contains:
- info about how the files have changed
- a reference to the commit that came immediately before it
- an SHA-1 hash code

The repo contains the files. The act of copying a repo from a remote server is called cloning. <br>
The process of downloading a repo from a remote server is called pulling. <br>
The process of uploading a repo to a remote server is called pushing. <br>

## Branches
They are a way to detach you work from the master branch. <br>

## README.md
It's a file that contains information about other files in a directory or archive of computer software. <br>

## Git commands
**git add** = add files to the staging area <br>
**git rm --cached "file_name"**	= remove files from the staging area <br>
**git rm -f "file_name"** = remove files from the working directory <br>
**git push --force** = force the push, overwriting the remote repository <br>
**git fetch** = tells if there are changes on the remote server <br>
**git pull --force** = force the pull, overwriting the local repository <br>
**git log** = shows the history of commits <br>
**git checkout -b "branch_name"** = create a new branch <br>
**git checkout "branch_name"** = switch to a branch <br>
**git switch "branch_name"** = switch to a branch <br>
**git pull origin "branch_name"** = pull a branch from the remote repository <br>
**git push origin "branch_name": "branch_name"** = push a branch to the remote repository <br>
**git revert HEAD** = undo the last commit <br>
The HEAD is a pointer that holds your position within all your different commits. <br> 
Using HEAD~n you can go back n commits. <br>
**git stash** = temporarily removes changes. <br>
**git rebase** = reapply commits on top of another base tip. <br>
**git submodule** = allows you to keep a Git repository as a subdirectory of another Git repository. <br>
**git submodule update** = update the submodules. <br>