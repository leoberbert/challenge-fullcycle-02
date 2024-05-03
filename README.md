# Desafio Full Cycle 

Para execução deste projeto será necessário primeiramente cria a network que utilizaremos para comunicação entre os containers:

```shell
docker network create net-dev
```

Em seguida, dentro da pasta do nosso projeto, executar o comando:

```shell
docker-compose up -d
```

Agora basta acessar a URL abaixo em sua máquina local:

http://localhost:8080