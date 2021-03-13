# Composer Base Image
Imagem base para build de aplicação php.

## Build

Criar imagem base
```sh
docker build -t yurih567/composer:2.7.4 base
```

Roda o shell na imagem criada
```sh
docker run -it --rm yurih567/composer:2.7.4 /bin/sh
```

## Release

Envia imagem para o hub.docker
```sh
docker push yurih567/composer:2.7.4
```
