# Projeto de conteinerização de app web java

Esse é um projeto de conteinerização de um app web em java que usei para aprender um pouco sobre docker.

# Requisitos
- Uma máquina virtual com ubuntu 18.04. Nesse projeto usarei uma ec2.
- Instalar Docker e docker compose na sua máquina virtual.
- Ter as imagens padrão de memcached e rabbitmq.

# Instalando docker e docker-compose
No primeiro passo instale docker e docker-compose, você pode fazer isso seguindo as documentações.
- https://docs.docker.com/engine/install/ubuntu/#set-up-the-repository

# Memcached e rabbitmq
Logo após fazer os primeiros passos dê um docker pull nas imagens padrão de memcached e rabbitmq com os seguintes comandos:
- sudo docker pull memcached
- sudo docker pull rabbitmq

# Últimos passos
Dê um git clone nesse projeto, e então entre na pasta Projeto-container-docker. Você notará que o arquivo do docker-compose estará nessa pasta.
Então tudo pronto, digite o seguinte comando:
- sudo docker compose up

# Verificando o funcionamento do projeto.
Logo após isso seu terminal ficara inutilizável pois o projeto não esta rodando em background.
Pegue o ip publico da sua maquina virtual e coloque no google com :8080 no final (Ex: 168.192.1.1:8080).
- ⚠️Lembre-se de liberar a porta 8080 para seu ip no security group que está sua máquina virtual.⚠ 



### Pronto, crie uma conta no site e verifique se está tudo ok. :)
