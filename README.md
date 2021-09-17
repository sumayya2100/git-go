# git-go
Question 1: Agile Vs DevOps

Answer:

In Agile, we work iteratively and repeat these stages in each sprint of a release cycle:
-	Design
-	Develop
-	Test

After a defined/planned number of sprints, once we are ready with a version of the application/program, we release it and then finally Deploy in production. 
While in DevOps, we perform all these stages continuously in an iterative manner:
-	Design
-	Develop
-	Test
-	Deploy

Note: Major design is done prior to developing the software, however, design tweaks due to new features or feature enhancements, continues throughout the process.
-------- ----- --------

Question 2: Define CI, Continuous Delivery & Continuous Deployment


Continuous Integration: 

This means to continuously merge code changes, from all developers working in a team, in a central repo, and running automated test and builds on it. The automated tests enables a team to catch issues faster which in turn reduces the time taken to resolve the issues and continue with the process without wasting any time.

Continuous Delivery:

After CI, code changes can be deployed to a test environment (using branching strategy other than master) to ensure that we always have a build ready to be deployed in production. The release build is then manually deployed in production.

Continuous Deployment:

Once the changes are approved from CI/CD, the code can be deployed to production, in an automated way without manual intervention. With continuous deployment, we also gather continuous feedback from the user which we can timely incorporate into our upcoming builds. 

-------- ----- --------

Question 3: What are the benefits of Cloud Computing?

Answer:

The benefits of Cloud Computing include:

-	Easy Resource management – No need to buy the resources, just get them as and when needed.
-	Easy to increase/decrease resources according to the need.
-	Pay per use facility 
-	Self-service facility

-------- ----- --------

Question 4: Difference b/w Git & GitHub

Answer:

Git – is a software; a distributed version control system for managing the source code. Used for collaboration as well as tracking code changes. 

GitHub – is a service; for Git repo hosting. It has the complete functionality of git’s version control system and Source Code Management system, along with its own additional features, such as user management.  

-------- ----- --------

Question 5: Stages of Git

1.	Working directory: This is where the user works on their local machine. This directory contains the .git folder, that you can create through the git init command. once that is done, this local directory is tracked by git. 

2.	Staging area: It's the area where files are added to be committed to git, but havent been committed or pushed in the git repo. Use the git add command to add the files to stagin area. Until the files are committed, there will be no metadata or hash. Staging is not permanent, only  used to ‘stage’ the code. 

3.	Local repo: This is where the code resides when committed using the git commit command. The files are still in the local machine and have not been pusdhed to the remote git repo. 

4.	Remote repo: This resides on the server. It is basically a clone of the local git repo, hosted in GitHub. git push command is used to push the changes from local to remote repo. 

-------- ----- --------


