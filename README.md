# Bootcamp #01 Qualiters Club 

Teste de API Rest do manual a CI/CD

## O que é: 

Este repositorio foi criado para o bootcamp de teste do API Rest

## Tecnologias

- Postman versão web
- Node version v18.16.1
- newman 5.3.2
- newman-reporter-html

## Documentações 

Doc da API: [Consulte Swagger](https://serverest.dev/#/)

 ## Como instalar o ambiente

- Prmeiro: Instale o node no seu computador [baixe aqui](https://nodejs.org/en/download).

- Segundo: realize a instalação do newman de forma global [baixe aqui a dependencia](https://www.npmjs.com/package.newman)

  ```
  npm install -g newman
  ```

- Terceiro: realize a instalação da dependencia dos relatórios (opcional) [newman-reportorter-html](https://www.npmjs.com/package/newman-reporter-html)

  ```
  npm install -g newman-reporter-html
  ```

 Como rodar os testes

### Pelo Postman web ou desktop

 - importe a collection e a environment
 - Execute os testes de forma manual ou automizada

### Pelo newman

- Abra o console de preferência

- Execute a seguinte linha de comando para rodar os testes

  ```
  newman run ServerRest.postman_collection.json -e ServerRest_env.postman_environment.json -r cli
  ```

- Execute  os testes com relatório  

  ```
  newman run ServerRest.postman_collection.json -e ServerRest_env.postman_environment.json -r cli,htmlextra
  ```

  ### Report

  Se você optou por rodar os testes com o report htmlextra, você gerou um aquavit html com o resultado dos testes e para verificar as validações você pode abriri a pasta **newman** que foi criada no local em que os arquivos de collection e enviroment se encontram.

  

   Entre em contato

 - e-mail: bytes1991@outlook.com

- Redes Sociais: https://www.linkedin.com/in/afonso-silva-77a49465/
