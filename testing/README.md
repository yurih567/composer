# Composer Image for Testing
Imagem base para testar aplicação php.

## Build

Criar imagem base
```sh
docker build -t yurih567/composer:2.7.4-testing testing
```

Roda o shell na imagem criada
```sh
docker run -it --rm yurih567/composer:2.7.4-testing /bin/sh
```

## Release

Envia imagem para o hub.docker
```sh
docker push yurih567/composer:2.7.4-testing
```
