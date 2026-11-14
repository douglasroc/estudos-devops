* `docker run` -> Para executar um container
docker container run -> para executar um comando
docker container ls -> para listar containers apenas, não mostra container finalizados
docker container ls -a -> o parametro -a é para listar imagens inativas. Para
docker container run --name meucontainer -> Para nomear o nome do container
docker container rm -> Para apagar ou excluir um container pelo ID ou pelo nome apos o rm
docker ps -a -> O docker ps tem a mesma função de listar containers porém é mais resumida, porém tem a mesma função do docker container ls
docker container run -it ubuntu /bin/bash
 --> comando -it para criar o container em modo interativo
docker container run -t ubuntu /bin/bash
<<<<<<< HEAD
 --> comando --rm -it para criar o container em modo interativo e quando sair do container excluir a imagem
=======
 --> comando -t para criar o container em modo interativo
docker container run -t ubuntu /bin/bash
 --> comando --rm -t para criar o container em modo interativo e quando sair do container excluir a imagem
docker container run -d nginx --> para rodar em background modo deamon plano de fundo em segundo plano
>>>>>>> 5097c2f (adicionado comando docker container run -d)
docker exec -it <imagem> --> para executar uma imagem up
docker container run -d -p 8080:80 nginx
 --> comando para adicionar a porta deve utilizar o -p depois o número da porta.
docker container stop <imagem> ou docker container start --> um comando serve para parar e o outro para iniciar
docker container ls -qa --> comando serve para listar apenas os id das imagens
docker container rm -f <imagem> --> o -f é para forçar a remoção da imagem sem precisar parar
docker container rm -f 
--> comando para eliminar todos os containers de uma só vez (Ele remove forçando, todos os containers que seriam listado pelo comando ls -qa
