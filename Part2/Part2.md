# Part2

<br>
1. List three major version control software for software engineering. 
<li>Git
<li>Apache Subversion
<li>GNU Bazaar
<li>Mercurial
<li>Plastic SCM
<li>CVS
<br>
<br>
2. What are the main advantages to using Git in your software development, and how is it useful for game developers. 
<li>One of the biggest advantages of git is it's branching capabilities git branches are often easy to merge, also github has distributed development so
each developer working on a project with different branches will get their own local repository, this can be usefull for gamedevs because 
a game developer would want different branches to delegate work within a branch to more developers also so a dev can ensure the quality of code before commiting to a main branch.
<br>
<br>
3. Define the following terms in relation to Git. Branch, Pull, Push, repository, working copy, merge 
<li>Branch: A branch in git is a new area of a repository,branches are always made from an existing main branch
<li>Pull: A pull command in git gets current content that is in a remote repository and immediately updates to any changes that were made in a your local repository to match
<li>Push: The push command in git is how you upload any changes made to a repository from your local repo to your remote repo
<li>Repository: A repository is a place where you can store a projects files,code and revision history
<li>Working Copy: A working copy in git is where your current work and files are stored so you can interact with them
<li>Merge: Merging in git is how you get two different branches to get back together again merging the two branches into a single branch
<br>
<br>
4. If you are working at a company, which of their policies and procedures might relate to using version control systems such as Git. 
<li>Best practice for version control
<li>WHS(work health and safety)
<li>Workplace Harassment and Bullying Policy (HR department)
<li>Operational Procedures
<li>Cyber Security procedures
<li>Privacy Policy
<li>Codes Of Conduct
<br>
<br>
5. Merge conflicts can occur while using git. List merge tools or diff tools you can use to help you merge and deal with conflicts. 
<li>Diff Checker
<li>Win Merge
<li>Meld
<li>Diff,Diff3
<li>P4Merge
<li>Beyond Compare
<br>
<br>
6. In a merged source code file, how does Git let you know there is a conflict?
<li>Git will produce a log that that tells us all the commits that will conflict between the merged branches.
<li> you will see a Head header where you will see <<<<<<<<< HEAD (this represents the current change)
<li> and you will see the incoming branch on the incoming branch >>>>>>>>> branch name 
<li> it should say specificly which files/changes are conflicting in the terminal
<br>
<br>
7. What are the steps you can take to resolve Git conflicts? 
<li>You can use merge tools to try finding how the conflicts came about
<li>check the status of the merge with the git status command, this will help you identify the conflict
<li>use the command git reset to reset conflicted files into a good unconflicted state
<li>now that you know which files are conflicted make the changes you need to make then commit them again
<br>
<br>
8. What does git revert do, and how can you use it? 
<li>git revert Instead of deleting or orphaning commits in the commit history, a revert will create a new commit that inverses the changes specified.
<br>
<br>
9. What does git reset do, and how can you use it?  
<li>git reset undoes any changes you've made in your working directory to get back to a specific commit while throwing away any other commit you've made after the specific commit your are trying to locate.
<br>
<br>
10. What is the difference between git revert and git reset? 
<li>revert doesn't delete commits instead it makes a new commits which changes the error, git reset reverses commits made to a specific commit and deletes any commits made after
<br>
<br>
11. True or False: It is okay to commit broken code to the main branch.
<li>False
<br>
<br>
12. True or False: You should commit related changes. For example, fixing two different bugs should produce two separate commits.
<li>true
<br>
<br>
13. Describe what is DevOps, how is it useful for game developers?
<li>Devops are a group of practices, tools and philosophies that help automate and integrate the processes between software development and Developers
<br>
<br>
14. List what tools can be used with DevOps. Give a brief description of each one. (at least 3) 
<li>Jira
<li>DynaTrace
<li>Jenkins
<br>
<br>
15. What is CI/CD and how can it be used to automate the game development process? 
<li>CI/CD stands for continuous integration and continuous delivery and it can be used when doing game development to quickly release a prebuild of a game while still making regular changes to it
