Exercise 7: Branching and Merging
=================================

1. Type *git checkout -b my_branch*
2. Type *git branch* to show the available branches (master and
   my_branch)
3. Create a new text file called *my_branch.txt* and put in the
   following text: "This is the file containing information about my
   branch."
4. Type *git add my_branch.txt*
5. Type *git commit -m "Add text file for my branch."*
6. Type *git checkout master*
7. Type *git merge my_branch*.
8. Type *ls* to verify that my_branch.txt is now
   present in your master branch
9. Type *git hist* to see the branch/merge
10. Type *git branch -D my_branch*
11. Type *git branch* to verify that my_branch is gone
