Part Three: GitHub Pages and Static Sites
------------------------------------------

1. GitHub Pages

GitHub allows you to turn any repository into a web-page. There are two
kinds of web-pages, one for a user, and one for a particular project.
I use the two kinds of pages on my website. The user-level page has a
**username.github.io** URL (e.g.
[https://redlibrarian.github.io](https://redlibrarian.github.io)), while
project-level pages has a **username.github.io/repository** URL (e.g.
[https://ualbertalib.github.io/dsc_git_workshop](https://ualbertalib.github.io/dsc_git_workshop).

You *can* do some of the setup for a github page in the GitHub settings
section, but I find it easier to manage from the director you're working
in.

[Exercise 11: Your First GitHub Page](exercises/exercise11.md)

You can make GitHub pages as elaborate as you like, except that they
have to be static (i.e. they can't be backed by a database, and they
can't use server-side scripting, like PHP). There are many sophisticated
static-site generators you can use, like [Jekyll](https://jekyllrb.com/)
and [Hugo](https://gohugo.io/). If you're interested in minimal
computing and digital libraries, you can deploy a [Wax
site](https://minicomp.github.io/wax/) (which uses Jekyll) to GitHub
pages. 

2. Static Sites with Reveal.js

At it's most basic, creating a static site with Jekyll, Hugo, or
something else follows the exact same steps we did a moment ago: create
a project directory and repository, fill the directory with files,
commit the changes, and push the results. If you want to use something
that's already built, like Jekyll or Hugo, though, you have to add a
step to the front of the list: getting the software that you need. Each
software package has different ways of doing that, some more or less
complicated. Take a look at the Quick Start instructions on the [Jekyll
web site](https://jekyllrb.com). For this exercise, we're going to start
with something a little simpler: a PowerPoint alternative called
Reveal.js, which I've been using for presentations for years.

In order to get started with Reveal.js, there are two things you can do.
In the first place you can go to the [Reveal.js GitHub
repository](https://github.com/hakimel/reveal.js/) and "fork" the
repository. This makes a copy of the repository under your own account
that you can modify independently of the original version (if, later on,
you decided some of your changes were useful enough to be merged back
into the original, you would issue a Pull Request. That's mainly how
contributing to Open Source software works today). A slightly simpler
way to do it is to download the Reveal.js code from the repository. On
the page, you should see a green button that says "clone or download".
Click on that and choose Download Zip. This downloads all the Reveal.js
code in a zipped archive. Once that's downloaded, unzip it to a location
that you will know how to get back to.

Once you have unzipped the directory, go to the command line and **cd**
into the directory. Once there, initialize the repository with **git**
init. Then proceed to 

[Exercise 12: Creating a Reveal.js
presentation](exercises/exercise12.md)
