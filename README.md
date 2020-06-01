# Git Basics

This practice will help you get comfortable with basic git operations: making changes and publishing them.

We will learn the following git operations:

- `add` changes to the staging area
- `commit` changes
- `push` local commits to publish them to GitHub
- `pull` changes from the remote repository
- 'branch' create a new branch named "branch-1" and push to Github

Other useful commands to see what is going on the git repository:

- `status`
- `log`

## Exercises

- [x] Fork this repo
- [x] Clone this repo
- [x] Update the README: add some lines to the end and push them to GitHub
- [x] Create a new file called `newfile.txt`, add some contents to it and push it to GitHub
- [x] Update newfile.txt and push the changes to GitHub
- [x] Open the repository on GitHub and make changes to `newfile.txt`
- [x] Pull the changes to your local repository
- [x] Create a new branch named "branch-1" and push to Github

## Practice Output 
1. Your repo url in Github

   https://github.com/Cendeal/git-basic.git

2. Your answer for What is the difference between `add`, `commit`, and `push`?

   - definition is different

     `add` use to add file contents to the index, in fact. if you execute this command it will change your local .git/index file and create a new directory in .git/object to record what have changed.

     `commit` use to record changes to the repository

     `push` use to update remote refs along with associated objects as local

   - using order is different.

     For example, if you have changed something in your local, you need to `add` first,

     and then `commit` your changes, finally `push` your commit.

   - scope is different.

     `add` and `commit` just in local. If you do not push, it will not change anything into remote
