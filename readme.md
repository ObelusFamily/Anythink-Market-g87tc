# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Clone this repository to your local machine
Install Docker - https://docs.docker.com/get-docker/

### validation
Run docker -v to get docker version
Run docker-compose -v to get docker-compose version
### Set Up Docker
Run docker-compose up from your local project directory

After docker is done setting up yout image check following links:
http://localhost:3000/api/ping - pointing to your browser
http://localhost:3001/register - pointing to a sign up page that should work now
