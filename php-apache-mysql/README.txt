Create this directories structure:
.
├── docker-compose.yml
├── Dockerfile
├── dump
│   └── myDb.sql
├── sessions
└── www
    └── index.php



#criar o conteiner com base no arquivo docker-compose.yml 
docker-compose up -d

#Para o conteiner com base no arquivo docker-compose.yml 
docker-compose stop

#Excluir o conteiner com base no arquivo docker-compose.yml 
docker-compose rm

# para e remove os containers
docker-compose down

#Ver o conteiner com base no arquivo docker-compose.yml 
docker-compose ps

#Rodar o canteiner do Composer para executar comandos:
docker-compose run composer bash

# acessa o terminal de um container
docker container exec -it NOME-CONTAINER bash

#Visualizar os volumes persistentes:
docker volume ls

#Remover um volume:
docker volume rm NOME-VOLUME

COMPOSER
#Iniciar o composer em uma pasta
composer init

#Instalar as dependencias
composer install

#ver versão do composer
composer -V





    