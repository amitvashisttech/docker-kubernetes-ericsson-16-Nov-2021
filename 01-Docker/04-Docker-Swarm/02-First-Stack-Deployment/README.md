```   
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
```

