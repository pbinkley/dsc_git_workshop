Exercise 1
==========
   * Create a directory
   * Any way you know how, make a text file in that directory called "exercise1.txt" containing the sentence: *This is
     the only sentence in the file.*
   * Make a second text file called ".gitconfig" in the directory which contains the following lines (we will walk through this step in the workshop):
   ```
   [alias]
       hist = log --pretty=format:'%h %ad | %s%d [%an]' --graph --date=short
   ```

   * At the command line, move to the directory you created
   * Type *git init*
   * Save [this file](/.gitconfig) into the directory.
   * Type *git add exercise1.txt*
   * Type *git commit -m "Add first text file."*
   * Edit your file again and add the following sentence: *Now this file
     contains two sentences.*
   * At the command line, type *git add exercise1.txt*
   * Type *git commit -m "Add sentence to file"*
   * Type *git hist* - What does it say? Note the code in the first
     column of each line: that's a [hexadecimal
     number](https://en.wikipedia.org/wiki/Hexadecimal) (base 16) used
     as an identifier for a particular revision.
   * Type *git checkout <bottom-most code>*
   * Take a look at your *exercise1* file, it should only have the first
     sentence.
   * Type *git checkout master* and look at your file again, the second
     sentence should be back again.
    
 Concepts: commit, commit message, history, checkout, HEAD, master.
