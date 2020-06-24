# Task1_MLOPS
This is for the task1 of MLOPS course from linux world India

Here is the task:

JOB#1
If Developer push to dev branch then Jenkins will fetch from dev and deploy on dev-docker environment.

JOB#2
If Developer push to master branch then Jenkins will fetch from master and deploy on master-docke environment.
both dev-docker and master-docker environment are on different docker containers.

JOB#3
Manually the QA team will check (test) for the website running in dev-docker environment. If it is running fine then Jenkins will merge the dev branch to master branch and trigger #job 2


To know how I completed the task check images_task folder 
You can also visit my linked in article where I have explained the project in Detail
Here's the link: https://www.linkedin.com/pulse/integrating-jenkinsdocker-git-hub-creating-automated-web-patnaik
