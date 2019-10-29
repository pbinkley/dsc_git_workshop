Exercise 2
==========

* In your git project directory, create a second file called
  "master.txt" and put some text into it.
* Type *git add master.txt*
* Type *git commit -m "Add master.txt"*
* Type *git co -B new_branch*
* Type *git co branch* to list available branches: master and new_branch
* Create a third text file called "new_branch.txt"
* Type *git add new_branch.txt*
* Type *git commit -m "Add new_branch.txt"*
* Type *git co master* - the file new_branch.txt should be gone.
* Type *git merge new_branch* - the file should now appear.
* Type *git rm new_branch.txt* 
  Type *git branch -D new_branch*
  
  Conceots: branches, creating a new branch with *co -B*, moving between
  branches, merging branches, deleting branches, deleting files.
