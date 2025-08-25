# Bootcamp 001 Qualiters Club 
Teste de API Rest do manual ao CI/CD 


## O que é
Este repositório foi criado para o bootcamp de teste de API Rest.

## Tecnologias Utiizadas
- Postman
- node v22.15.0
- newman v6.2.1
- newman-reporter-html

## Documentação

- Doc da API [Consulte Swagger](https://serverest.dev/)

## Como instalar o ambiente

- Primeiro: instale o node no seu computador [baixe aqui](https://nodejs.org/pt/download)
- Segundo: realize a instalação do newman de forma global [baixe aqui a dependencia](https://www.npmjs.com/package/newman)
```
npm i -g newman
```
- Terceiro: realiaze a instalação da dependencia dos relatórios (opcional) [newman-reporter-html](https://www.npmjs.com/package/newman-reporter-htmlextra)
```
npm i -g newman-reporter-htmlextra
```
## Como rodar os testes

### Pelo Postman Web ou Desktop
- Importe a collection e o environment
- Excecute os teste de forma manual ou automatizada

### Pelo newman
- Abra o seu console de preferência
- Execute a seguinte linha de comando para rodar os testes
  ```
  newman run ServeRest.postman_collection.json -e seveRest_env.postman_environment.json -r cli 
  ```
- Execute os testes com relatório
  ```
  newman run ServeRest.postman_collection.json -e seveRest_env.postman_environment.json -r cli -r html
  ```
### Report

Se você optou por rodar os testes por htmlextra, você gerou um arquivo html com o resultado dos testes e para verificar as validações você pode abrir a pasta **newman** que foi criada no local em que os arquivos de collection e envirornment se encontram.

## Contato

email: brunomoscosorodrigues@gmail.com
linkedin: https://www.linkedin.com/in/bruno-moscoso/
  
