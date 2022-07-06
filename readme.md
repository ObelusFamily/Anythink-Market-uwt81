# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

 1. Clone this repository to your local machine.
 2. Install [Docker for Desktop](https://docs.docker.com/get-docker/).
 3. Verify docker is ready by running the following commands in your terminal: 
    - `docker -v` 
    - `docker-compose -v`
 4. Run `docker-compose up` from the project root directory to load Anythink's backend and frontend
 5. Test that the system is up by visiting: http://localhost:3000/api/ping
 6. Register a new user in: http://localhost:3001/register