1. Install docker. sudo apt install docker.io
2. Install docker-compose. sudo apt install docker-compose
3. git clone <this repository>
4. Cd into direcotry with the docker-compose.yml file
5. run, docker-compose up -d
6. once running run docker exec -it librenms bash
7. vi config.php
8. add, $config['enable_syslog']=1;

   
