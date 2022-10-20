## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
2. What is the difference between Git and GitHub?
3. Why do we create a branch? 
4. What is the purpose of a Pull Request?
5. What is the command you can use to switch between branches? For example you are working on FIRSTNAME-LASTNAME branch and you want to switch back to main.
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
7. What is a merge conflict?
8. How do you resolve a merge conflict?

Answers:
1. Git is a version control system that allows users to access previous versions of code. It 
also allows users to develop new iterations of code in parallel with a main branch of code, 
then merge once the changes are satisfactory.
2. Git is the version control system that technically anyone could implement, GitHub is the 
company/website most people use to access this system. 
3. A branch allows us to work on a copy of the main code, which allows the main code to run as 
is while we make changes. When we have made the changes we need we can merge the branch and 
main to form an updated main.
4. A Pull Request is the last stop (hopefully) before your branch merges back with the main 
branch. It notifies the others you are working with that you have made changes and they are ready 
for review.
5. git checkout 'main'
6. 'git fetch' allows you to grab all the new branches and commits of others working on your shared repository. 'git merge' combines 
your local work with any other changes made on that branch online. 'git pull' performs both 'git fetch' and 'git merge'.
7. A merge conflict happens when two changes are made to the same code and you must decide which change will be final.
8. You must fix the conflict on your local clone repository then push the changes to the branch stored on GitHub.
