# desafio-go-docker
Desafio 01 - Docker Fullcycle.

Nesse desáfio eu precisei criar uma aplicação simples em GO que printa na tela uma mensagem (Full Cycle Rocks!!), o desáfio estava na criacão
de uma imagem no Docker que tenha menos que 2MB de tamanho, depois de uma pesquisa descobri que a imagem mais minimalista que existe é a
imagem scratch, ela não possui nenhum sistema operacional. Com (-ldflags "-s -w") não é necessario um sistema operacional, o arquivo
possui por si todas as dependencias necessárias.

Nome da imagem no Dockerhub ---> andremigotto/fullcycle ( https://hub.docker.com/repository/docker/andremigotto/fullcycle/general )
