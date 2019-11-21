Exercise 10: Issues
===================

1. Click on the Issues tab, then New Issue to create an issue.
2. Enter a title and a description and hit submit. Notice the options on
   the right hand side: Assignees, Labels, Projects, and Milestone.
   Assignees allows you to assign collaborators to particular issues,
   either to assign a task or to get input into the task; labels allows
   you to label the task; projects and milestones allow you assign the
   tasks to particular larger projects or project phases.
3. Notice the number the issues gets assigned. This is important. Also
   notice that you can close issues without deleting them, allowing you
   to keep track of tasks that were accomplished. This can be used for
   documentation purposes.
4. Return to your project directory and create a new file containing
   some text. 
5. Enter **git add .**
6. Enter **git commit -m "Closes #whatever-issue-number-was-assigned"**
7. Enter **git push origin master**. Now check your issues list in
   GitHub. You should see that your issue was closed, with a link to the
   commit that closed it.
8. Notice that you can make simple changes and commits within GitHub itself. Find the file you just committed on the **Code** tab, and click on it to view. Then click on the edit button (pencil) at the top right hand corner of the view window, make some changes to the file.
9. At the bottom of the window, there is a box where you can type a commit message, and then a "commit changes" button. Enter a message and then hit **Commit Changes**.
10. Back in the view window, click the "History" button to see all the changes you have made to this one file, including the linked (closed) issue.
   
