Lesson 2A: Basic Workflow
=========================

The following lesson uses the metadata records in the [records](records)
directory.

[Exercise 4: Starting a Project](exercises/exercise4.md)
--------------------------------------------------------

The start of every project using git starts with selecting a directory
(either creating a new one, or choosing an already existing one),
initializing it as a git repository, adding/modifying files, and committing
changes.

[Exercise 5: Adding files](exercises/exercise5.md)
--------------------------------------------------

In exercise 4, you created a new README file and added it to your
repository. You can also copy files into the directory and then commit
them to the repository.

[Exercise 6: Removing files](exercises/exercise6.md)
----------------------------------------------------

When you add files, you can't just put them into a directory and commit
them, you have to add them first (with *git add*). Otherwise, they are
present within your directory, but *not* present in your repository (in
other words, they aren't subject to version control). There are times
when you want to explicitly exclude some files from version control, and
we will look at those reasons later.

When you want to remove files, the same logic applies. You can't just
delete a file from the directory and commit. In exercise 6 you saw what
happens when you try that. Instead, you have to tell git to remove the
file (with *git rm*) and then commit that change.

[Exercise 7: Branching and Merging](exercises/exercise7.md)

When you are making changes to multiple files that are all part of a
single large change you are making to your project, such as adding a new
feature to a software application, or perhaps writing a version of a
document for a different audience, you can use branches to keep the
different versions separate. If later on you want to merge your changes
with the main project (which happens often in software projects, for
example), then you can merge your branch with the master branch. If
changes are made to the master branch that you want to incorporate into
your branch, then you can merge the master branch with your branch.

[Exercise 8: Reverting Changes and History](exercises/exercise8.md)

Sometimes you make changes by mistake or that you change your mind
about. In order to undo those changes after you have committed them, you
can revert to a previous commit. Note that this operates at the level of
*the commit* not the individual files, so reverting a commit will undo
all changed files that were part of that commit.

There are other ways you can change the history of a repository, but
this can be dangerous if changes are not well-defined. It can also make
the history harder to read/understand. More sophisticated ways to change
the history of an existing repo are outside the scope of this tutorial,
but there is a lot of information online.
