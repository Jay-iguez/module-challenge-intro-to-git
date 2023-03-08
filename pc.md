## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
2. What is the difference between Git and GitHub?
3. Why do we create a branch?
4. What is the purpose of a Pull Request?
5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
7. What is a merge conflict?
8. How do you resolve a merge conflict?

1. Git is an open-source version control system (otherwise known as a VCS). It's responsible for
every change that happens locally on your computer with any involved source code. Not only does it store the changes, but it also comprehensively logs them that then allows developers to go back and pull up the changes and branch out on them for continual development. 
2. Git is a productive way for developers to keep track of changes made to source code and collaborate on it. It's a great way to track the development of and work on a piece of software for example in an engaging way. GitHub however is essentially a cloud based way to save all those changes made using Git to the internet. It allows not just for local development, but global developement. It enables developers to work with one another in a better, and streamlined manner with all the benefits of Git.
3. A developer creates a branch in Git to make a snapshot of a specifc change they desire to work on, off the main repo of code in question. It furthers development by enabling the testing of new features or de-bugging already present code without touching the main branch of work that many developers need intact. Different developers can work off the main branch without ever negatively impacting one another.
4. A Pull Request allows developers to directly compare code off loaded from a diverging branch with the main branch. It then can allow not only a detailed message on what changes were made, but also for a detailed discussion between involved developers to see if the discussed code within a local branch can be fully commited to the main branch.
5. To switch bewtween branches using Git, one would use the command "git checkout + BRANCHNAME". For example if I wanted to switch from the FIRSTNAME-LASTNAME branch to the main branch I would type in Git "git checkout main" my CLI would then look like "$ git checkout main".
6. 'git fetch' adds changes from the remote repository to your local working branch WITHOUT commiting them, while 'git pull' would immediately update the local repository to match said content. 'git merge' is a way of putting independent forked history from branches back together again in a single branch.
7.  A merge conflict occurs when two different developers attempt to merge their individual branches into a single one with conflicting code involving a shared file. For example added or removed code to a text file.
8. To solve a merge conflict, you first must find the competing line of code bewteen the two branches by going into the local Git repo that has the merge conflict, generate a list of files affected by the merge conflict for example "git status", open said files in a text editor of choice, find conflicting lines of text by the appearance of "<<<<<<<", find the difference in code between "=======", and decide to keep what lines of code you want to then finally add and commit to the main branch. 