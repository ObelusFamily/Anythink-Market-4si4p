# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1) Clone this repository
2) Install [Docker Desktop](https://docs.docker.com/get-docker/)
3) cd into project root directory
4) Run `docker-compose up`
5) Test that everything is up and running:
    * Open [http://localhost:3000/api/ping](http://localhost:3000/api/ping) on your browser
    * Go to [http://localhost:3001/register](http://localhost:3001/register) and create a user
