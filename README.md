# Projeto de conteinerização de app web java

Esse é um projeto de conteinerização de um app web em java que usei para aprender um pouco sobre docker. <br/>
O projeto basicamente é uma conteinerização simples de uma aplicação web em java usando o docker e docker compose. <br/>
Nele criei imagens docker customizadas para nginx, Tomcat e sql e 2 imagens oficiais de memcached e rabbitmq.

# Requisitos
- Uma máquina virtual com ubuntu 18.04. Nesse projeto usarei uma ec2 t2.small (Recomendo usar instância de no mínimo 2 gb de ram).
- Instalar Docker e docker compose na sua máquina virtual.

# Instalando docker e docker-compose
No primeiro passo instale docker e docker-compose, você pode fazer isso seguindo as documentações.
- https://docs.docker.com/engine/install/ubuntu/#set-up-the-repository

# Docker compose
Dê um git clone nesse projeto, e então entre na pasta Projeto-container-docker. Você notará que o arquivo do docker-compose estará nessa pasta.
Então tudo pronto, digite o seguinte comando:
- sudo docker compose up

# Verificando o funcionamento do projeto.
Logo após isso seu terminal ficara inutilizável pois o projeto não esta rodando em background.
Pegue o ip publico da sua maquina virtual e coloque no google com :80 no final (Ex: 168.192.1.1:80).
- ⚠️Lembre-se de liberar a porta 80 para seu ip no security group que está sua máquina virtual.⚠ 

Para logar na conta adm use:

Login: admin_vp <br/>
senha: admin_vp

ou crie uma conta e teste.

### Pronto, verifique se está tudo ok. :)
