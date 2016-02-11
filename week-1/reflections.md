#1.1 Think About Time Reflection
During my research on time management and productivity ideas, two that stuck out to me were meditation, “making it big by starting small” (or use of a Minimum Viable Product), and time boxing.  Although I have always heard people praising the benefits of meditation, I had no idea how simple and beneficial it can be.  By using a simple meditative habit like focusing on one’s own breathing (focused-attention meditation) for a few minutes a day, you can significantly reduce anxiety and stress.  Another concept I read about was using a “minimum viable product” when approaching complex problems.  By breaking the complex problem into parts, you not only allow yourself to be more organized, but you will also be less likely to make a mistake.  Time Boxing refers to a predetermined period of time during which an individual or a team will work towards completing a goal.  Rather than working until the goal is completed, a time box tells the individual or team to stop working once the time box has ended.  This will allow you to take breaks and not spend too much time being stuck on one particular aspect of the coding process.  I currently manage my time using a calendar, which has been pretty effective thus far.  I do however plan to impose time boxing on myself to ensure I do not spend hours caught up on a minute aspect of the codign process.  I also plan to start meditating, and have downloaded the Getheadspace app.  I plan to use all three of these techniques during my time in Phase 0.

#1.2 The Command Line Reflection
1. What is the shell, what is "bash"?

The shell is essentially an approachable way to handling and understanding the what's going on inside your computer system.  Users can also customize their shells so that certain tasks done on a daily basis can be done so more efficiently.  Essentially, the shell is a more efficient way of navigating and making changes to your computer.  In terms of what "bash" is, I am using windows and have not come across this as of yet, only briefly during the hour-long video.

2.  What is the most challenging for you in going through these materials?

So far, it is understanding how to put these commands together to form a bigger picture (especially in terms of syntax).  It is easy enough to understand conceptually what each command does.  Also Windows and Mac differences.

3. Were you successfully able to use all the commands?

Yes.

4.  In your opinion, what are the most important commands and arguments to know?

-Understanding how to navigate directory trees: cd, cd .., cd../

-Understanding how to manage directories: mkdir, rmdir, mv

-Understanding pipes and redirection: |, <, >

5.

pwd - prints working directory

ls - lists out the files in the current directory

mv - moves a file

cd - changes directory

../ - moves back a directory 

touch - for mac, but it creates a blank file. Off top of my head its new-item on windows

less - shows the contents of a file ("more" on windows)

rmdir - removes a directory

rm - removes a file

help - brings up the manual on commands, shows various information on syntax, environment,  etc.

#1.4 Forking and Cloning Reflection
Let's say we have a file that we would like to make into a new repository.  You can do this using the command line using the git command "git init file_name".  This will create a .git folder inside the file you were turning into a repo and enables version control for the repo.  To fork a repository on github, you first must navigate the github web interface to locate the repo you want to fork (create a stand-alone copy of that repo on your own github account).  Once you have located the repo, click on it.  Then on the top right of the site, you will see the button "Fork" - click it.  This will create the forked repo and the site will redirect you to the forked repo.  If you would like to make changes to the repo, however, you will need to clone a copy of the forked file onto your local computer.  On the forked repo's github page, there will be a box displaying a URL, mine says HTTPS, go ahead and copy that URL to your clipboard.  Go to the command line and type git command "git clone URL" (substituting URL for the copied fork url).  This will create a clone of the file on your local system.  

I actually did not run into any problems when setting up my github account and completing the challenges.  I found it rather straightforward.  I am sure it will be harder to understand when dealing with multiple developers working on the same repo.