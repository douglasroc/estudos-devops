* `docker run` -> Para executar um container
docker container run -> para executar um comando
docker container ls -> para listar containers apenas, não mostra container finalizados
docker container ls -a -> o parametro -a é para listar imagens inativas. Para
docker container run --name meucontainer -> Para nomear o nome do container
docker container rm -> Para apagar ou excluir um container pelo ID ou pelo nome apos o rm
docker ps -a -> O docker ps tem a mesma função de listar containers porém é mais resumida, porém tem a mesma função do docker container ls
docker container run -t ubuntu /bin/bash
 --> comando -t para criar o container em modo interativo
docker container run -t ubuntu /bin/bash
 --> comando --rm -t para criar o container em modo interativo e quando sair do container excluir a imagem
