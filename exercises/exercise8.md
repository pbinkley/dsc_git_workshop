Exercise 8: Reverting Changes and History
=========================================

1. Open my_branch.txt in a text editor and add the line "this text added
   by mistake".
2. Type *git add my_branch.txt*
3. Type *git commit -m "Update my_branch.txt file"*
4. Type *git hist* to see the history so far. Copy and paste the id of
   the last commit ("Update my_branch.txt file")
5. Type *git revert <commit id>"* and hit enter.
6. Take a look inside the my_branch.txt file to ensure that the line you
   added is gone.
7. Type *git hist* to see the new history. What do you notice?
