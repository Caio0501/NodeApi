# node-api

## Desenvolvendo uma Api em nodejs é mongodb

projeto criado com o intuito de construir uma api basica ultilizando de recursos como nodeJs, docker, mongodb e express...

## Uso

Para executar este projet e necesario ter o mongodb rodando no docker ou no pc, caso esteja deseje ultilizar o Docker bastar executar:

```
docker pull mongo
```
para adiquirir a imagen do mongodb é:
```
docker run --name mongodb -p 27017:27017 -d
```
para dar run no mongodb pela primeira vez caso ja tenha a imagen basta executar
```
docker start mongodb
```
uma vez que o mongo estiver rodando basta executar o comando 
```
npm run dev
```
