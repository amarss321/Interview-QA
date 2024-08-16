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
