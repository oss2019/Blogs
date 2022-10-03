IF YOU DON'T KNOW GITHUB DONT'T WORRY WE WILL START FROM SCRATCH!!

SO BE READY FOR THE JOURNEY 
LETS BEGIN!!

GitHub consis tof the two main things .
1---> Version Control
2---> Git

Now first of all what is Version Vontrol.

Let's see what is version Control:-

 *   Version control helps developers track and manage changes to a software project’s code. As a software
     project grows, version control becomes essential.
 *   It is not good to directly edit the main file similar as our rough work you want to just try to solve
     a question but you will not directly attempt it on the main notebook , you first try it on rough note book then if you were able to get the desired solution you write it in the Main Notebook.   
 *   Similar to the above analogy Branches are their in the version control if you want to add some
     funtion to  the main program you first make a diffrent branch edit what ever you want now if it is working properly then you can merge it in the main branch.  
 *   All the previous edits ans the files which you are edited are stored in the version control.


Now second Question is What is Git?

Let's see what is Git:-

*   Git is a specific open-source version control system created by Linus Torvalds in 2005.
*   Specifically, Git is a distributed version control system, which means that the entire codebase and history is available on every
    developer’s computer, which allows for easy branching and merging.


Now final question Whats is Github then?

*   GitHub is a for-profit company that offers a cloud-based Git repository hosting service. Essentially, it makes it a lot easier for
    individuals and teams to use Git for version control and collaboration.
*   GitHub’s interface is user-friendly enough so even novice coders can take advantage of Git. Without GitHub, using Git generally
    requires a bit more technical savvy and use of the command line.


FOR THE GITHUB INSTALLATION YOU CAN VISIT THE OFFICIAL WEBITE OF THE GITGUB
https://docs.github.com/en/desktop/installing-and-configuring-github-desktop/installing-and-authenticating-to-github-desktop/installing-github-desktop


There are many things to learn in the git but here we will be focusing on the the syntax of the basic git commands.
All the commanda here given are run on the terminal

Note:-<Name>  indicate the Name you want to give


* For checking version of the git installed
Syntax-------> git --version


* For  changing the name associated with your account 
Syntax------> git config --global user.name"<Name>"


* For  changing the name associated with your account 
Syntax------> git config --global user.emai"<Email>"


*  For initiation of the any folder in the git
Syntax-----> git init 


*  For initialzing the new directory
Syntax------> mkdir <Name>


*  For making new file 
Syntax------> echo > "<Name>"


*  For checking status of file
Syntax------> git status

* For adding all the files in the staging area
Syntax------> git add .


*  For adding file in (staging area)
Syntax------> git add <Name>


*  For commiting the file
Syntax------> git commit -m "<message>"


*  For knowing all commits you made
Syntax------> git log

*For going to the previous version
Syntax------> git checkout hashcode/filename

*For going to last commit
Syntax------> git checkout master
 
*For knowing branches
Syntax------> git branch
 
*For making new branch
Syntax------> git branch <name>
 
*For creating new branch and move directly
Syntax------> git checkout -b <Name>
 
*For merging this branch
Syntax------> git merge branchName
 
* For ignoring pushing this file git
Syntax------> touch .gitignore
 inside gitignore write the name of the file which you don't want to send in git


//If any one has updated the repository on the git hub and you are also working on it then you can update the file stored in your local macine my
Syntax------> git pull origin branchname
 
*For  pushing the code for 1st time in that branch
Syntax------> git push  --set -upstream origin branchname
 
From 2nd time for pushing we can use  
Syntax------> git push
 
 
* For  unstaging the file 
Syntax------> git restore --staged <Name>       //  git restore filename
Syntax------> git rm –chached <name>
 
* For initializing any folder from specific git url
Syntax-----> git remote add origin <url>










  