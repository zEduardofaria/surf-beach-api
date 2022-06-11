<p align="center">
  <img alt="typescript" title="#Typescript" src="./assets/cover.png" />
</p>

<h1 align="center">
   <a href="#"> Surf Beach API </a>
</h1>

<h3 align="center">
    It's just a project for study!
</h3>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/zEduardofaria/surf-beach-api?color=%2304D361">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/zEduardofaria/surf-beach-api">
  
  <a href="https://github.com/zEduardofaria/surf-beach-api/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/zEduardofaria/surf-beach-api">
  </a>
    
   <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen">
   <a href="https://github.com/zEduardofaria/surf-beach-api/stargazers">
    <img alt="Stargazers" src="https://img.shields.io/github/stars/zEduardofaria/surf-beach-api?style=social">
  </a>
</p>

<h4 align="center"> 
	 Status: In progress
</h4>

<p align="center">
 <a href="#about">About</a> •
 <a href="#features">Features</a> •
 <a href="#tech-stack">Tech Stack</a> • 
 <a href="#user-content-license">License</a>

</p>

## About

This API delivers previsions of surf, like others sites such as [Magicseaweed](https://magicseaweed.com/), where we can look for information about specific surf beaches, or point to you which beach is great to surf in a specific time and region

This project was intended to be a way to improve my skills in creating APIs, among other things like:

- TS
- TDD
- Clean architecture
- Jest Mocks
- External services integration
- JWT Auth flow
- MongoDB + Mongoose
- Github Workflows
- Rate Limit
- Open API documentation

---

## Features

- [x] Auth

  - [x] Sign in
  - [x] Sign up

---

### Pre-requisites

Before you begin, you will need to have the following tools installed on your machine:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/),
In addition, it is good to have an editor to work with the code like [VSCode](https://code.visualstudio.com/)

#### Running the Backend (Server)

```bash

# Clone this repository
$ git clone git@github.com:zEduardofaria/surf-beach-api.git

# Access the project folder cmd/terminal
$ cd surf-beach-api

# install the dependencies
$ yarn install

# Create a .env file based in .env-example

# Create a .env.test file based in .env-test-example

# Run the application in development mode
$ yarn start:dev

# The server will start at port: 3333 - go to http://localhost:3333

```

#### Testing (Server)

```bash

# Restart DB, and run it again with Docker compose
$ yarn test:e2e

```

## Tech Stack

The following tools were used in the construction of the project:

#### **Server** ([NodeJS](https://nodejs.org/en/) + [TypeScript](https://www.typescriptlang.org/))

- **[Express](http://expressjs.com/)**
- **[Jest](https://jestjs.io/)**
- **[MongoDB](https://www.mongodb.com/)**
- **[Heroku](https://www.heroku.com)**
- **[Github Actions](https://github.com/features/actions)**

> See the file [package.json](https://github.com/zEduardofaria/surf-beach-api/blob/master/package.json)

#### **Utilitários**

- Editor: **[Visual Studio Code](https://code.visualstudio.com/)**
- API Test: **[Insomnia](https://insomnia.rest/)**

---

## License

This project is under the license [MIT](./LICENSE.md).

Made with love by Eduardo Faria 👋🏽 [Get in Touch!](Https://www.linkedin.com/in/eduardo-fariasilva/)

---
