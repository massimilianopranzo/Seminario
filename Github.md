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
*git add* = add files to the staging area <br>
*git rm --cached "file_name"*	= remove files from the staging area <br>
*git rm -f "file_name"* = remove files from the working directory <br>
*git push --force* = force the push, overwriting the remote repository <br>
*git fetch* = tells if there are changes on the remote server <br>