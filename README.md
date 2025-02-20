# Referral App

![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Fastify](https://img.shields.io/badge/fastify-%23000000.svg?style=for-the-badge&logo=fastify&logoColor=white)

O Referral App é um sistema de indicações onde é possível se cadastrar em um evento e fazer indicações com seu ID, contabiliza essas indicações e cria um ranking dos participantes que mais indicaram pessoas. Projeto feito utilizando Node.js, Fastify, biblioteca Zod, Postgresql e Redis como banco de dados. ORM Drizzle e Swagger para documentação.

Projeto desenvolvido durante evento da Rocketseat


## API Endpoints
A API fornece os seguintes endpoints:

```markdown
API Disponível na porta http://localhost:3333

POST /subscriptions - Criar participante

GET /invites/{id} - Link de convite (redirect)

GET /subscribers/{id}/ranking/clicks - Contador de clicks no link

GET /subscribers/{id}/ranking/count - Contador de usuários convidados pelo participante

GET - /subscribers/{id}/ranking/position - Posiçção do participante no ranking de convites

GET - /ranking - Ranking dos participantes que mais convidaram

```

Fique a vontade para clonar o projeto, fazer sugestões, entrar em contato :)

## Contato

[![](https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/claytonbentes/)
[![](https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white)](mailto:claytonjhony.bentes@gmail.com)
