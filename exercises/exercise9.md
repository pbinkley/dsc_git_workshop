Exercise 9: Creating a GitHub account and repository.
=====================================================

1. Go to [GitHub](https://github.com) and enter a username, email
   address, and password.
2. Once you have successfully logged in, create a new repository (click
   the "+v"button in the top right hand corner).
3. Give the repository a name. Creating a respository in GitHub is
   similary to creating a project directory and running **git init**
   inside it.
4. Notice that you can give your repository an option description,
   choose whether you want the project to be public or private,
   initialize the repository with a README file, a .gitignore file, or a
   license (we will talk about those in a minute).
5. Once you hit "create repository", there are a few more things to
   notice:
   - "Get started by creating a new file or uploading an existing file.
     We recommend every repository include a README, LICENSE, and
     .gitignore." A README gets displayed on the main page of your
     repository (take a look at [this workshop's
     repository](https://github.com/ualbertalib/dsc_git_workshop). The
     box below the list of files contains the contents of the README.md
     file. A LICENSE can be one of a number of software licenses. GitHub
     gives you a list to choose from or you can supply your own.
     Licenses are beyond the scope of this workshop. There are plenty of
     articles explaining licenses, including this [Wikipedia
     article](https://en.wikipedia.org/wiki/Software_license) and [this
     page from GitHub](https://choosealicense.com/). A .gitignore file
     tells git not to track certain files (e.g. password files, local
     configuration files). They're useful for not cluttering up your
     project with files specific to your computer or workflow, and for
     not including sensitive information.
   [[-]] "create a new repository on the command line": this is usually how
     I go about creating a new project and repository. Notice that the
     steps are the same as the ones we used in previous exercises (init,
     add, commit). The main differences are 1) **git remote add** (which
     specified the GitHub location in your local project directory) and
     **git push** which uploads your project to GitHub.
   - Also notice the tabs across the top: Code, Issues, Pull Requests,
     Actions, Projects, Wiki, Security, Insights, and Settings. We won't
     go through all of these, but we'll look at the main ones: Code,
     Issues, Pull Requests, and Settings.
   - This repository is empty. Go ahead and follow the instructions for
     "push an existing repository from the command line" on your local
     project directory. Once you have issued the **git push** command,
     notice how this repository page changes.
