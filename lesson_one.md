Part One: Concepts
------------------

1. What is git?

   [git](https://en.wikipedia.org/wiki/Git) is a "distributed version control system for for tracking changes in source code during software development". Basically, what this means is that git can be used similarly to the "track changes" function in word: keeping track of any changes made to a file or set of files and allowing you to revisit previous iterations of those files. Initially developed for programming source code, git can be used to track any kind of file, though it works best with plain text files (course code, HTML, markdown, etc). 

3. Version/revisionControl

   Version control refers to the ability to track, manage, and return to
   different versions of your project (code, documents, etc.). These
   versions can be sequential (i.e. iterative changes made over time to a single
   document or set of documents) or "horizontal" (i.e. functional
   changes made to a document or set of documents). The difference
   between these two concepts is that sequential differences can be
   understood as changes made to the same objecti (though beware of the
   [Ship of Theseus](https://en.wikipedia.org/wiki/Ship_of_Theseus)
   problem)., and revisions can be
   understood as iterative. Two move through different revisions, think
   of fast-forwarded or rewinding a cassette (is this too old of a
   reference?). By contrast, horizontal revisions can often be thought
   of as fundamentally changing the object, by adding or removing
   features, or fundamentally redesigning the object.
   
   When dealing with sequential changes, we usually refer to the process
   of keeping track and managing changes as "revision control", because
   you're revising the document(s) you're working on, rather than making
   wholesale changes. Think of this as the equivalent to tracking
   changes in a Word document; when changes are accepted, they are
   merged into a new revision of the document.
   
   Horizontal changes usually produce entirely new *versions* of the
   object. In this case we might speak of "version control", because you
   aren't simply revising an object or set of objects, but making
   changes that may make the new version incompatible with the old one.

   Git helps to manage both kinds of changes, starting with allowing you
   to keep track of *revisions*, but also allowing you to keep track of
   *versions*. In both cases you can move back and forth between
   revisions, and sideways between versions.
   
   Spatial Metaphors:
<pre>   
   |--------|----------|-----------------|---|----------|----|-------------
   1        2          3                 4   5          6    7
   
                                       |
   ------------------------------------------------------------------------
   |                |                   |                  |
   For students     For faculty         For the media      For the public
</pre>
   [Exercise 1](exercises/exercise1.md)
   
1. Branching

   Your commmit history shows you the revisions - backwards and forwards
   \- in a single line of revisions (see spatial metaphors above). But in
     addition to a single, sequential set of changes, you can make
     horizontal changes. Horizontal versions occupy different
     *branches*, each with its own revision history. So you can see how
     the two spatial metaphors above can actually intersect, with sets
     of horizontal changes occupying different branches within a given
     project, with sequential histories running backwards and forwards
     along each branch.
     
     [Exercise 2](exercises/exercise2.md)
     
2. Collaboration

    Committing, branching, and merging means that multiple people can
    work on the same project (even the same files) at once. Git's
    merging system is able to reconcile different changes to the various
    files. If you get a conflict, the system warns you and gives you a
    chance to fix them. It's possible to do this kind of decentralized
    collaboration just using git, but in practice most people centralize
    their projects in a repository on GitHub, making it easier to
    conceptualize *where* revisions are stored and changes are made. We
    will look at working with/in GitHub in the next section, but first
    we will do some more work just within git to get used to it.
    
    [Exercise 3](exercises/exercise3.md)

