Exercise 11: Your First GitHub page.
------------------------------------

1. Create a new branch called **gh-pages** (**git checkout -b
   gh-pages**)
2. Create a new file called **index.html**
3. Add the following to the index.html file:
  ```
  <html>
    <body>
      <h1>This is my first GitHub page</h1>
      <p>This is a bit of text.</p>
      <p>And now we're done</p>
    </body>
  </html>
  ```
4. Save the file, then add and commit it.
5. When we push, we don't want to push to the master branch, so in this
   case type **git push origin gh-pages**.
6. In your browser, go to **username.github.io/respository-name**. It
   sometimes takes a while for the page to build, so keep refreshing the
   page until you see it.
