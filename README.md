# curso-protractor-tat
![Lint and tests](https://github.com/JoaoArthurDeveloper/CursoProtractor/workflows/Lint%20and%20tests/badge.svg)

Projeto para o curso de Protractor da Escola TAT

## Pré-requisitos

É necessário que os seguintes sistemas estejam instalados para a execução do projeto

- Node.js(`12.16.3`) e NPM(`6.14.5`)
- Navegadores Google Chrome(`81.0.4044.138`) e Mozilla Firefox(`76.0.1`)

## Instalação

Após clonar o projeto, acesse o diretório do mesmo e execute `npm install` para instalar as dependências de desenvolvimento.

## Executando os testes

Execute `npm run pretest:local && npm test` para executar os testes em modo _headless_ em ambos os navegadores Chrome e Firefox.

### Executando os testes em um navegador específico

#### Chrome

Execute `npm run pretest:local && npm run test:chrome` para executar os teste em modo _headless_ somente no navegador **Chrome**.

#### Firefox

Execute `npm run pretest:local && npm run test:firefox` para executar os teste em modo _headless_ somente no navegador **Firefox**.

___

Um projeto da [Escola Talking About Testing](https://talkingabouttesting.coursify.me). 
