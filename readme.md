# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Install Docker , you can verify it is installed by running `docker --version` and  `docker-compose -v`.
2. Under the root the project run ```docker-compose up -d```
3. If docker is  working correctly , you should be able to access <http://localhost:3000/api/ping>

## Container

Also you can use `docker exec` to run commands inside the container.
