# Gitpod
Our cloud based IDE or integrated devlopment environment

Gitpod is an amazing service with a great free offering. It is based on Microsoft Visual Code but based in the cloud. 
It allows us to automatically set up a virtual machine in the cloud with an existing github project already installed.
This means we can write code from our browsers without having to install anything on our machines.
The first thing to do is to load a project. This can be done using a URL.
Go to https://gitpod.io/#github.com/rml1997/developercourse and log in with your GitHub account.

The menu bar on the left hand side consists of the following icons: explorer, search, git, debug, and extensions.
Explorer shows the folder structure of the project on github
Search allows you to search through files for specific words or regular expressions
Git shows which files have changed, allows you to stage files (get them ready to commit), commit them and push them to GitHub
Debug helps you to track down bugs in your code on the server
Extensions allow you to install extra tools to work in your IDE

Clicking on the > next to a folder will expand its contents, and clicking a filename will display it in the top right window.
Right click on 2.gitpod, click new file, and give it a name.
When you create or edit a file, a green U will be shown next to it to let you know that it has unstaged changes.
These are changes that aren't being tracked by git. To get them into GitHub, there are a few steps which must take place.
The first step is to stage the changes in a file. This lets git know that a file should be included in a commit.
The next step is to commit the changes. This updates your "local" (on gitpod for us) git repository with the changes.
The final step is to push the changes. This brings the remote repository (GitHub) up to date with the local one.

Click on the Git icon (Y with circles) on the left hand menu
You should see a list of changes with a U next to them. 
You can hover your mouse over the filename to stage a single file or the word "changes" to stage all changes at once.
You should see a + which will stage the change. Click it.
You should now see the file or files move to Staged Changes with an A beside it.
Once you have staged all the files associated with the commit, you will need to write a commit message.
This needs to go in the box labelled Message and should include issue tracker ids if one is used (we'll get to that soon)!
Commit messages are used to describe the changes within a commit.
You can click the tick at the top to commit all the changes.
You should then click the ellipsis (...) and click push to update GitHub.

Congratulations! You've just committed your first file to GitHub!