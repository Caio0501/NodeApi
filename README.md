# node-api

## Desenvolvendo uma Api em nodejs e mongodb

projeto criado com o intuito de construir uma api básica utilizando de recursos como nodeJs, docker, mongodb e express...

## Uso

Para executar este projeto é necessário ter o mongodb rodando no docker ou no pc, caso esteja deseje utilizar o Docker bastar executar:
```
docker pull mongo
```
para adiquirir a imagen do mongodb é:
```
docker run --name mongodb -p 27017:27017 -d
```
para dar run no mongodb pela primeira vez caso já tenha a imagem basta executar
```
docker start mongodb
```
uma vez que o mongo estiver rodando basta executar o comando
```
npm run dev
```
