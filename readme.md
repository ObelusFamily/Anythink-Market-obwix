# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. [Install docker](https://docs.docker.com/get-docker/).
2. Verify docker is ready by running the following commands in your terminal: `docker -v` and `docker-compose -v`
3. Run `docker-compose up` from the projects root directory
4. After it's done running, check if the backend is runnning by going to http://localhost:3000/api/ping
5. Check if front-end is running by creating a user: http://localhost:3001/register

