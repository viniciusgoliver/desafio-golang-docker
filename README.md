
# Desafio Full Cycle Módulo Docker

## Desafio Golang Docker

- Esse desafio é de fato empolgante principalmente pra quem ainda não vivenciou as aventuras com o Golang!
  
  * Vamos precisar publicar uma imagem no docker hub. 

Quando executarmos:

```bash
docker run <seu-user>/golang-docker

```

Temos que ter o seguinte resultado: Fullcycle Rocks!

- Lembrando que a Go Lang possui imagens oficiais prontas, vale a pena consultar o Docker Hub.

- A imagem de nosso projeto Go precisa ter menos de 2MB =)

# Build

```
docker build -t <seu-user>/golang-docker .
```

# Pull

```
docker pull <seu-user>/golang-docker
```

# Executar o container

```
docker run --rm <seu-user>/golang-docker
```

## Observações

- Para utilizar a minha imagem do dockerhub. modifique o <seu-user>/ para viniciusgo/  conforme abaixo.

```bash

docker pull vinciusgo/golang-docker
docker run --rm viniciusgo/golang-docker

```
