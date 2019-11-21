Lesson 2B: Adding GitHub
========================

Git is essentially a *decentralized* system, meaning that any repository
can be shared in multiple locations and kept in sync using **git
commit** and **git push**. However, most people like to work in a
centralized way by using GitHub as a cloud-storage solution for their
repositories. GitHub allows you to upload your repositories, but also
has additional features like issue-tracking, project-based wikis, etc.

[Exercise 9: Creating a GitHub account and
repository](exercises/exercise9.md)

Before moving back to our project folder, we're going to explore some of
the things GitHub adds to your project.

Issues are ways to track problems to be solved, features to be added, or
can be used as to-do lists. One of the useful features of Issues is that
you can link them to particular changes in your project. 

[Exercise 10: Issues, Pull Requests, and
Settings](exercises/exercise10.md)

We won't do a hand's on exercise for Pull Requests. But it's good to
know what they are. Let's say you're collaborating on a project and each
member is working on a separate branch. We looked at branching and
merging in an earlier exercise, but what if you wanted a way to check
and approve (or disallow) a merge before it took place. A Pull Request
creates an issue for a particular branch to be merged into the master
branch. It signals to a collaborator that a change, feature, fix, or
other piece of work has been completed and should be reviewed before
merging it into the main project.

Settings are where you can set up information and processes for your
project/repository as a whole. You can assign collaborators, manage
notifications, etc. A lot of this is quite technical (e.g. deploy keys).
It's also where you can turn a project into a web-page, as we'll see in
the next lesson. Finally, settings is where you can change the
visibility of the project, transfer the project to someone else, or
delete the repository (see the "Danger Zone" section at the bottom of
the page).

One thing I want to mention here is that you can use GitHub as part of
your Research Data Management workflow. Not only can GitHub be used to
store research data itself (RED FLAG), but you can also use GitHub as a
place to backup your project files and as a version control system.

For example, in my research I'm interested in discourse analysis, so my
research data might include video or audio interviews, published texts,
etc, as well as transcripts and analysis work done in an NVivo project.
I can store all of that in GitHub, which will give me a) a backup of my
project and b) the full revision history of the work that I've done.

RED FLAGS: There are two main caveats here, one technical and one
social or ethical. The technical caveat is that git/GitHub work less
well with files that are very large or are not plain text (i.e. binary
files). Before deciding to use GitHub for backup or version control of a
particular project, you should consult with e.g. the Research Data
Management team at the library.

In terms of ethics, there are a few things to consider. First, GitHub is
now owned by Microsoft, but even prior to that, you should be leery of
putting sensitive information, private, or personally identifying data
on a third party website. If you're working with PII, again, talk to the
library, as we have locally hosted secure repositories for particular
kinds of sensistive information. Additionally, GitHub repositories
default to public and there is a limit to the number of collaborators
you can have on a private repository. All this to say that it's
important to consider not only the technical limitations of a tool you
might want to use, but also its social and ethical implications.
