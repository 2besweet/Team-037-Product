Empower Farmer

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/f4f54e902f3c40daa2b3ab0b77a65da0)](https://app.codacy.com/gh/BuildForSDG/Team-037-Product/dashboard)

## About

Empower farmer app that helps fund farmer by connecting farmer to sponsor and help farmer sell their product.

## Why
Tech solutions that can help give your local community access to international/advanced farming practices that will help them improve their infrastructure or farming practices.

## Usage

## Heroku Deployment

Application was deployed to Heroku. Use public URL [https://sdg-empower-farmer-frontend.herokuapp.com/](https://sdg-empower-farmer-frontend.herokuapp.com/) with API endpoints.

## Setup

### Getting started

* You need to have Git, Node, NPM and Docker installed on your computer.
* Installing [Node](node) automatically comes with npm.

### Clone

* Clone this project to your local machine `https://github.com/allebd/swapi.git`
  > Run the command below

```shell
   git clone https://github.com/allebd/swapi.git
```

### Setup

* Installing the project dependencies
  > Run the command below

```shell
   npm install
```

* Create a .env file similar to the .env.sample file

* Create your database
  > Run the command below

```shell
  npx sequelize db:migrate
```

* Add tables to database
  > Run the command below

```shell
  npm run db:reset
```

* Start your node server
  > Run the command below

```shell
  npm start or npm run dev
```

* Use `http://localhost:8000` as base url for endpoints


### Running Unit Test

* Run test for all endpoints
  > run the command below
  
```shell
  npm test
```
## Authors

[Joshua Lugada - Mentor]
[kolade ore - TTL](https://github.com/koladeore)
[Uche - FRONTEND-DEVELOPER](https://github.com/teezyfortune)
[Chinomso Onyeukwu - FRONTEND-DEVELOPER](https://github.com/2besweet)


## Contributing
If this project sounds interesting to you and you'd like to contribute, thank you!
First, you can send a mail to buildforsdg@andela.com to indicate your interest, why you'd like to support and what forms of support you can bring to the table, but here are areas we think we'd need the most help in this project :
1.  area one (e.g this app is about human trafficking and you need feedback on your roadmap and feature list from the private sector / NGOs)
2.  area two (e.g you want people to opt-in and try using your staging app at staging.project-name.com and report any bugs via a form)
3.  area three (e.g here is the zoom link to our end-of sprint webinar, join and provide feedback as a stakeholder if you can)

## Acknowledgements

buildforsdg@andela.com
https://buildforsdg.andela.com/projects


## LICENSE
MIT

