
<h1 align="center">
  <img alt="GoBarber" title="GoBarber" src="8c13dc2618dbd7f76d1d574350b98fdee1335ce5" width="300px" />
</h1>
<h3 align="center">
  GoStack: GoBarber Backend - API Rest com NodeJS/Express
</h3>
GoBarber é o projeto desenvolvido durante o BootCamp GoStack da Rocketseat. Uma aplicação completa feita com Node, ReactJS e React Native para gestão de um salão de beleza. 
<p></p>

## :rocket: Tecnologias
- [**NodeJS**](https://nodejs.org/en/)
- [**Docker**](https://www.docker.com/)
- [**Postgres**](https://www.postgresql.org/)
- [**MongoDB**](https://www.mongodb.com/) —
- [**Redis**](https://redis.io/) —
---


## **Blibiotecass**
- [**Express**](https://expressjs.com/pt-br/)
- [**Yup**](https://github.com/jquense/yup)
- [**Jsonwebtoken**](https://www.npmjs.com/package/jsonwebtoken)
- [**Sequelize**](https://sequelize.org/)
- [**Bcryptjs**](https://www.npmjs.com/package/bcryptjs)
- [**Date-fns**](https://date-fns.org/)
- [**Multer**](https://www.npmjs.com/package/multer)
- [**Nodemailer**]
- [**Bee-queue**](https://github.com/bee-queue/bee-queue)
- [**Sentry**](https://sentry.io/)
- [**Date-fns**](https://date-fns.org/)
- [**Youch**](https://www.npmjs.com/package/youch)
- [**Dotenv**](https://www.npmjs.com/package/dotenv)

---

## **Lint**
- [**ESLint**](https://www.npmjs.com/package/eslint) — [**Airbnb style guide (Javascript)**](https://github.com/airbnb/javascript)
- [**Prettier**](https://www.npmjs.com/package/prettier)
- [**EditorConfig**]() — Extension for VSCode.

---
## **Funcionalidades**
<h3>1. Criação e autenticação de usuários </h3>
Criação de usuários que podem ser usuários normais ou fornecedores (Provider). Ambos possuem e-mail e senha, além de dados pessoais, e são autenticados na aplicação com o uso do JWT. 

<h3>2. Agendamentos</h3>
Os usuários podem fazer o agendamento com um prestador de serviço, de acordo com os horários disponíveis do prestador em questão. O prestador de serviço é notificado na aplicação quando recebe um novo agendamento e também é notificado por e-mail quando um agendamento é cancelado. 
<h3>3. Listagens</h3>
Os usuários podem listar todos seus agendamentos feitos. Já os prestadores podem verificar sua agenda para o dia em questão, como todos os agendamentos dos dia passados, atuais e futuros.


---
# Instalando Dependências

```

$ git clone https://github.com/mailsongarcia/gobarber
$ cd gobarber
$ yarn
$yarn sequelize db:migrate
$yarn dev


```

