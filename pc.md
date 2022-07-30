## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git? 
    Git is a version control system 
2. What is the difference between Git and GitHub? 
    Git is the actual program running on a coumputer, and GitHub is a remote "cloud" that hosts your code
3. Why do we create a branch? 
    We create a branch to seperate our own changes to the code from the main line of code as we work. 
4. What is the purpose of a Pull Request? 
    A pull request is there to ask someone to review and/or merge your branch's changes to the code into another branch
5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
    Git checkout, for this example it would be 'git checkout main'
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
    git fetch :
        allows you to fetch any changes to your local repository from the remote repository, but does not pull them into your working directory 
    git merge :
        merges two branches together again 
    git pull :
        pulls any changes to your local repository, and into your working directory from a remote repository
7. What is a merge conflict?
    A merge conflict happens when two branches cannot be merged together without interfering with their individual changes in some way
8. How do you resolve a merge conflict?
    You resolve a merge conflict by telling git which conflicting line of code you'd like to keep - you open the code in your local repo, change the lines to no longer conflict, and then re add/commit/push the file.
    Github also has it's own conflict editor to correct the conflicting lines of code from the remote repo. 
