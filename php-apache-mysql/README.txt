Create this directories structure:
.
├── docker-compose.yml
├── Dockerfile
├── dump
│   └── myDb.sql
├── sessions
└── www
    └── index.php



criar o conteiner com base no arquivo docker-compose.yml 
docker-compose up -d

Para o conteiner com base no arquivo docker-compose.yml 
docker-compose stop

Excluir o conteiner com base no arquivo docker-compose.yml 
docker-compose rm

Ver o conteiner com base no arquivo docker-compose.yml 
docker-compose ps

Visualizar os volumes persistentes:
docker volume ls

Remover um volume:
docker volume rm NOME-VOLUME





    