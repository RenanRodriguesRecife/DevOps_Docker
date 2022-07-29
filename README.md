Docker e Ubunto Server (06/2022)

### instalar:

```
sudo apt install docker.io docker-compose
```

docker.io - básico para rodar o docker

docker-compose - usado para subir container usando o docker files.



### fazer o docker iniciar junto com o sistema e habilitar seu uso sem reiniciar o servidor

```
sudo systemctl enable --new docker docker.socket containerd
```
### help

```
docker --help
```

https://hub.docker.com/ - repositório comunitário com imagens de várias aplicações e sistemas operacionais em containers.


## Mini-tutorial

Criar uma instancia local de wordPress

1 - Logar como root (Linux)
```
sudo su
```
2 - Baixar uma imagem do WordPress do DockerHub (se você não expecificar uma versão o comando vai tentar baixar a ultima imagem
```
docker pull wordpress
```
