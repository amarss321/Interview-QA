# Interview-QA

## Domain AWS

- Question: Explain the need to Cloudtrail in AWS? Do you use it in your current project? What are some con's with using cloud trail?
```
Using Cloud trail we can audit who is created resources and who deleted the resoures 
Cloud trail will store log by defultly 90 days 
If we want to more days we need to create cloud trail
```


## Domain Docker

- Question: You have a docker host (EC2 instance) which contains 6 docker containers running. If you restart the EC2 instance will the docker containers also be restarted?

```
No, By defult Docker Containers will not restart.
If We want to restart docker Containers whenever server restart. At the time.
we need to create Docker Conatiners with this flag --restart=always.
Continers will restart when server restart
```
- What are some key Devops KPIs that you monitor In your team today?
```
KIP - Key Performance Indicators
What I know based on KPI the three KPIs that our team is currently monioring are
- deployment frequency. ( How we deploy successfully to producation)
- percentage of deployment.( When we deploying to production how many of them are failing)
- meantime to failure recovery (If the service go down how fast our recovery)
```
- What is difference between git fetch and git pull ?
```
I have not used git fetch a lot in my day to day work but what i know the difference between git fetch and git pull
- git fetch will update matadata from remote repo to local repo. If we want to changes to working dir we need to do git "merge"
- If any updates on a remote repository, If we want to copy those changes from GitHub to both  local repository and into their working directory,
 at the time we need to use git pull command.
```

