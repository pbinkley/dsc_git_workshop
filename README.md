Introduction to Git and GitHub
==============================

Learning objectives:
- To understand the difference between git and GitHub
- To use git for version control and collaboration
- To use GitHub as a central respository
- To create a static website using GitHub pages

Prerequisites:
- Some familiarity working in the command line.
- Git installed on your laptop.

Part One: Concepts
------------------

1. What is git?

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
   
   [Exercise 1](exercises/exercise1.md)
   
4. Branching
5. Collaboration

