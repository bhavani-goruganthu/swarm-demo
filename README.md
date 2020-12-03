# docker swarm app
TODO: Build and run manually
- Needs local version of redis + mongo
- Run all services, visit port 4000

Build all images and push to dockerhub
- Update build instructions to push to your own dockerhub (probably super slow)
- quick command `npm run deploy`

# Running on EC2
- https://docs.docker.com/engine/install/ubuntu/ 
- sudo apt  install docker-compose
- git clone https://github.com/sfsu-csc-667-fall-2020/swarm-demo.git
- cd swarm-demo/
- sudo docker swarm init
- sudo docker stack deploy -c devops/docker-compose.yml message-app
