# Biblioteca-Back

Projeto desenvolvido com Express.js como parte do Desafio 5 da Formação em Tecnologia da Escola DNC.
Este repositório representa o Back-End da aplicação Biblioteca, com funcionalidades completas de gerenciamento de livros, integração com banco de dados e documentação via Swagger.

## Tecnologias Utilizadas
  - Node.js
  - Express.js
  - Swagger
  - dotenv
  - nodemon
  
## Hospedagens
 - Documentação Swagger (API Docs):
  https://bibliotecaback.vercel.app/doc/#/  
 - Front-End no Vercel:
  https://projeto-biblioteca-front.vercel.app
 - Front-End no Netlify:
  https://bibliotecadnc.netlify.app/

## Como rodar o projeto localmente
Pré-requisitos

Certifique-se de ter instalado:
```
    Node.js
    NPM
``` 
Passo a passo

- Clone o repositório:
``` 
    git clone https://github.com/seu-usuario/Biblioteca-Back.git
```
cd Biblioteca-Back

Configure as variáveis de ambiente:
  - Copie o arquivo .EXEMPLO.env:
  - cp .EXEMPLO.env .env
 Preencha com suas configurações (porta, URL do banco, JWT, etc).

Instale as dependências:
``` 
npm install
``` 
Execute o servidor em modo desenvolvimento:
``` 
npm run dev
``` 
Acesse a aplicação localmente:
``` 
    http://localhost:3500
``` 
## Documentação da API
Acesse a documentação interativa da API via Swagger:
http://localhost:3500/doc
Ou pela hospedagem oficial:
https://bibliotecaback.vercel.app/doc/#/

Créditos

Projeto desenvolvido para o Desafio 5 da Formação em Tecnologia da Escola DNC.
Aplicação construída com foco em aplicar na prática o conteúdo aprendido em back-end e integrações com front-end.
