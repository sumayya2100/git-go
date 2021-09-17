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
