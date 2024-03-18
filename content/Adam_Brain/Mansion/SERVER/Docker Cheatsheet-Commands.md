15-Mar-2024
tags :  #server #docker #devops 

### Commands

1. Basic
> [!runs docker image]
> docker run -p 5001:5000 \<link to repo>
> [-p (publish)   host:constainer]

2. In Detached mode
> [!runs basic docker in detached mode (no logs are shown)]
> `docker run -d -p 5001:5000 \<link>`
>          -d is for detached

3. See Logs
> [!Command to see logs] 
> `docker logs \<id>` (add id to see logs)
> or
> `docker logs \<first 4 chars of subsring>`

4. Follow logs
> [!Follow logs] 
> `docker logs -f \<id>` 
> (add id to see logs) 
> -f is for follow logs
> 

5. See Docker images on the machine
> [!Docker images on the machine]
> `docker images`

6. See all the running docker containers
> [!Running Docker Containers]
> `docker container ls`

7. See all containers
> [!See All local Containers]
>`docker containers ls -a`


8. Stop Containers
> [!Stop Containers]
> `docker container stop \<4char id>`

9. Pull images
> [!Pull Images]
````docker pull \<image name>````
> by default pulls latest image

10. Stop container
11. Pause Container
12. Kill Container
13. Docker system commands
14. Docker build
15. Docker Push
16. Docker network
17. Docker link
18. Docker create network
19. Docker Compose file -yml file

