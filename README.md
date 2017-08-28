# Matchmaking

## About

A simple game app. 2 players can connect and player a game of 'Goofspiel' or 'Blackjack'. Players can also see the stats of their past games, or others, on the profile pages.

## Getting Started

1. Install dependencies: `npm i`
2. Run migrations: `npm run knex migrate:latest`
  - Check the migrations folder to see what gets created in the DB
3. Run the seed: `npm run knex seed:run`
  - Check the seeds file to see what gets seeded in the DB
4. Run the server: `npm run local`
5. Visit `http://localhost:8080/`
6. Log In with one of the pre-made users from the seed file.

## Screenshots
Main page

![main page](https://github.com/eli-h/card-games-webapp/blob/master/docs/card%20game%20main%20page.png?raw=true)

Select Game Page

![select game page](https://github.com/eli-h/card-games-webapp/blob/master/docs/select%20game.png?raw=true)

Goofspiel Game Page

![goofspiel](https://github.com/eli-h/card-games-webapp/blob/master/docs/goofspiel.png?raw=true)

Blackjack Game Page

![blackjack](https://github.com/eli-h/card-games-webapp/blob/master/docs/blackjack.png?raw=true)

Profile Page

![profile page](https://github.com/eli-h/card-games-webapp/blob/master/docs/profile.png?raw=true)
## Dependencies

- Node 5.10.x or above
- NPM 3.8.x or above
- Body-parser
- Cookie-parser
- dotenv
- ejs
- express
- knex
- knex-logger
- morgan
- node-sass-middleware
- pg
