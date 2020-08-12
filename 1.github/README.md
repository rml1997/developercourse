# GitHub
Version Control System or VCS for short

GitHub will be where we store our code. 
Unlike a folder on your hard disk, GitHub keeps versions of your code as it develops.
The first step is to sign up for an account here: https://github.com/join

Git is a tool written by Linus of Linux fame. 
He wrote it to work more efficiently in teams, but it can get quite complicated.
Anyone can get a copy of the files in a public repository using git. 

GitHub works by creating a project. Each project has a repository which is where the code for the project is stored.
A project consists of branches which can be used to seperate code out as it reaches certain stages of readiness.
Historically, the main branch was called Master but this is sometimes renamed now due to alleged references to slavery.
This provides an opportunity to call the branch something more meaningful depending on the workflow being followed.
We will call our main branch release.

There are a number of workflows which can (and should) be followed when developing.
GitHub supports pull requests which allow control over what code is allowed into the release branch.
The idea of this is that a group of changed files can be submitted and reviewed before being allowed into the release branch.

Another important concept is forking. A fork can be thought of as a copy of the code to release a new version.
Sometimes people bootstrap their code by forking boilerplate code.
Sometimes people disagree about how a project is progressing and create a fork to develop their own version.
In order to create a pull request on someone else's project, a fork is created to base the pull request off.

For more information on Git, see the following: https://www.atlassian.com/git/tutorials/what-is-version-control

At this stage, it will be enough just to have a GitHub account. 