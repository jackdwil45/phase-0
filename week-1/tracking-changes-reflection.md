1. How does tracking and adding changes make developers' lives easier?
This allows developers to easily navigate the history of the repo, and will help them identify where bugs are located. 

2. What is a commit?
A commit is a save point when you are making changes to a repo.  When a commit is done, it creates a new spot on the repo's timeline and explains who did it and why (with a commit message).

3. What are the best practices for commit messages?
Commit messages should easily explain to other developers and yourself what changes were made at that commit.  The best practice is to have straightforward messages, usually in the form of commands.

4. What does the HEAD^ argument mean?
HEAD^ refers to the last commit made, followed by HEAD~3, HEAD~4, and so on.

5. What are the 3 stages of a git change and how do you move a file from one stage to the other?
The first stage, after getting a local copy of the repo on your system, is to make whatever the desired changes are to the repo files in your text editor. The second stage is that you add/stage those files for a commit using "git add file_name".  The third stage is to then commit your changes using "git commit -m "message"". Once this is done, you can push your changes to github using "git push origin"

6. Write a handy cheatsheet of the commands you need to commit your changes.
-git add <file name>
-git status
-git log
-git remote add origin <URL>
-git commit -m "message"
-git checkout branch_name
-git checkout -b branch_name

7. What is a pull request and how do you create and merge one?
After commits are pushed into github's cloud, other developers will use what's known as a git pull request to get the repository that includes the changes made.  This is done by selecting the "compare and pull request" button on github's interface (while you're in the repo that has recently recieved commits), and comparing the branches.  After filling out the short description (similar to commit message) you press "create pull request".  You can then merge the changes by selecting "merge pull request", which will merge your changes to the master.  You can then delete your old branch.

8. Why are pull requests preferred when working with teams?
You are able to see where your teammates have made changes, and are able to work on the file without making any actual finalized changes.  This is very helpful for double-checking/reviewing the changes made before merging them.