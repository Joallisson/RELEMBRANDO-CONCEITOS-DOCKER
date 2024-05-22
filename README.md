# RELEMBRANDO-CONCEITOS-DOCKER
Esse repositório foi criado apenas para listar alguns comenados docker básico

- CRIAR UMA IMAGEM DOCKER A PARTIR DE UM Dockerfile </br>
   docker build -t name-image . </br>

- LISTAR TODOS OS CONTAINERS  </br>
   docker ps -a </br>

- LISTAR APENAS OS CONTAINERS EM EXECUÇÃO </br>
   docker ps </br>

- LISTAR TODAS AS IMAGENS </br>
   docker images </br>

- CRIAR UM CONTAINER </br>
   docker run -p 3000:3000 name-image </br>

- CRIAR REDE DOCKER </br>
   docker network create nome-da-rede </br>

- CONECTAR UM CONTAINER A REDE </br>
   docker network connect nome-da-rede nome-do-container </br>

- LISTAR REDES DOCKER </br>
   docker network ls </br>

- CRIAR CONTAINER JÁ APONTADO PARA UMA REDE DOCKER </br>
   docker run -p 3000:3000 --network nome-da-rede nome-da-imagem </br>

- DETALHAR REDE DOCKER E LISTAR CONTAINERS CONECTADOS A ELA </br>
   docker network inspect nome-da-rede </br>

- PARAR A EXECUÇÃO DE UM CONTAINER </br>
   docker stop nome-ou-id-do-container </br>

