```
    1  ls
    2  docker node ls 
    3  docker service ls 
    4  docker service create --replicas 1 --name hello-swarm nginx
    5  docker service ls 
    6  docker service inspect hello-swarm
    7  docker service ls 
    8  docker service ps hello-swarm
    9  docker service scale hello-swarm=5
   10  docker service ps hello-swarm
   11  docker service scale hello-swarm=3
   12  docker service ps hello-swarm
   13  docker service rm hello-swarm
   14  ls
   15  cd 01-Docker/
   16  ls
   17  cd 03-DockerSwarm/
   18  ls
   19  mkdir 01-Service
   20  vim 01-Service/README.md
   21  cd ../../
   22  git add . ; git commit -m "01-Service"; git push 
   23  ls
   24  cd 01-Docker/
   25  ls
   26  cd 03-DockerSwarm/
   27  ls
   28  mkdir 02-First-Stack-Deployment
   29  ls
   30  cd 02-First-Stack-Deployment/
   31  ls
   32  vim docker-compose.yaml
   33  ls
   34  vim docker-compose.yaml 
   35  docker stack deploy -c docker-compose.yaml getstarted
   36  cd 
   37  docker stack ls 
   38  docker stack ps getstarted
   39  docker service ls 
   40  docker service ps getstarted_web
   41  docker stack ls 
   42  docker network ls 
   43  docker service inspect getstarted_web
   44  docker ps 
   45  docker stack ls 
   46  docker stack ps 
   47  docker stack ps getstarted
   48  docker network ls 
   49  docker network inspect getstarted_webnet
   50  ls
   51  docker network ls 
   52  docker network inspect ingress
   53  docker ps 
   54  docker network ls 
   55  docker network inspect bridge
   56  docker run -d --name test nginx
   57  docker sp 
   58  docker ps 
   59  docker network inspect bridge
   60  docker stack ls 
   61  docker stack rm getstarted
   62  docker stack ls 
   63  docker service ls 
   64  docker network ls 
   65  cd - 
   66  ls
   67  history > README.md
   68  vim README.md 
   69  cd - 
   70  cd docker-k8s-ericsson-27-Oct-2021/
   71  git add . ; git commit -m "01-Service"; git push 
   72  ls
   73  cd 01-Docker/
   74  ls
   75  cd 03-DockerSwarm/
   76  ls
   77  mkdir 03-Visualizer_with_App/
   78  cd 03-Visualizer_with_App/
   79  ls
   80  vim docker-compose.yaml
   81  ls
   82  docker stack deploy -c docker-compose.yaml myapp
   83  docker stack ls 
   84  docker service ls 
   85  docker service scale myapp_web=5
   86  docker service ls 
   87  docker service ps myapp_web
   88  docker service create --replicas 3 --name hello-swarm nginx
   89  ls
   90  history > README.md
```

