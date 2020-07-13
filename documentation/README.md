# Conceitos do Node

## O que é o Node.js?

- Javascript no back-end;
  - Não lidamos com eventos do usuário final;
  - Rotas e integrações;
- Plataforma (não linguagem);
- Construída em cima da V8;
- Comparável a PHP / Ruby / Python / Go;

## O que é o NPM?

- Instalar bibliotecas de terceiros;
- Fornecer bibiotecas;
- Por que utilizaremos o Yarn?
  - Ele está avançando mais rápido que o NPM em questão de funcionalidades;
- Comparáveis:
  - Composer do PHP;
  - Gems do Ruby;
  - PIP do Python;

## Características do Node

- Arquitetura Event-loop;
  - Baseada em eventos (Rotas na maioria das vezes);
  - Call Stack;
- Node single-thread;
- C++ por trás com libuv;
- Background threads;
- Non-blocking I/O;

<p align="center">
  <img src="../readme/call-stack.png" width="404" height="416">
</p>

## Frameworks

- ExpressJS como base:
  - Sem opinião;
  - Ótimo para iniciar;
  - Micro-serviços;
- Frameworks opinados:
  - AdonisJS;
  - NestJS;

# Conceitos API REST

## Como funciona?

- Fluxo da requisição e resposta:
  - Requisição feira por um cliente;
  - Resposta retornada através de uma estrutura de dados;
  - Cliente recebe resposta e processa resultado;
  - As rotas utilizam métodos HTTP:
    - <span style="color: #75f3d0;">GET</span> http://minhaapi.com/<span style="color: #BB227B;">users</span>
    - <span style="color: #75f3d0;">POST</span> http://minhaapi.com/<span style="color: #BB227B;">users</span>
    - <span style="color: #75f3d0;">PUT</span> http://minhaapi.com/<span style="color: #BB227B;">users</span>/<span style="color: #EDBE00;">1</span>
    - <span style="color: #75f3d0;">DELETE</span> http://minhaapi.com/<span style="color: #BB227B;">users</span>/<span style="color: #EDBE00;">1</span>

<p align="center">
  <img src="../readme/routes-resources.png">
</p>

## Benefícios

- Múltiplos clientes (front-end), mesmo back-end;
- Protocolo de comunicação padronizado (JSON);
  - Mesma estrutura para web / mobile / API pública;
  - Comunicação com serviços externos;

## Conteúdo da requisição

<p align="center">
  <img src="../readme/request-content.png" width="572" height="232">
</p>

## HTTP Codes

- <span style="color: #5097C2;">1xx</span>: Informational
- <span style="color: #489C8E;">2xx: Success
  - 200: SUCCESS
  - 201: CREATED
- <span style="color: #AD4A81;">3xx</span>: Redirection
  - 301: MOVED PERMANENTLY
  - 302: MOVED
- <span style="color: #E4C547;">4xx</span>: Client Error
  - 400: BAD REQUEST
  - 401: UNAUTHORIZED
  - 404: NOT FOUND
- <span style="color: #EF6E64;">5xx</span>: Server Error
  - 500: INTERNAL SERVER ERROR

> 💡 BORA CODAR!