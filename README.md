# BDD_python

## Rappel

Utilisation de SQL Alchemy qui est un ORM Object Relationnal Mapping : 
technique permettant de convertir des données entre des systèmes incompatibles
exemple: base de donnéee SQL avec langage Python

Instanciation Bdd dans docker (ici MySql)
 - docker pull mysql:latest (Pull MySql)
 - docker run --name=user_mysql_1 --env="MYSQL_ROOT_PASSWORD=root_password" -p 3306:3306 -d mysql:latest (Run le container)
 - docker exec -it user_mysql_1 mysql -uroot -proot_password (Utiliser MySQL sur le container)


Elastic et kibana :

Faire un docker-compose.yml
Faire un docker-compose up (30 minutes de dl)


