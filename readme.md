# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

To set up the repo, follow these steps:

1. [Install docker](https://docs.docker.com/get-docker/) on your developer machine

   - You can verify docker is ready by running the following commands in your terminal: `docker -v` and `docker-compose -v`

2. Navigate to your local clone of the repo. If you have not cloned one previously, do so by executing the following command on your terminal: `git clone git@github.com:ObelusFamily/Anythink-Market-cq5vb.git`

3. Run `docker-compose up` from the project root directory to load Anythink's backend and frontend

   - If Docker is working correctly, the backend should be running and able to connect to your local database, you can test this is up and running by pointing your browser to http://localhost:3000/api/ping

4. Now, it’s time to check the frontend and make sure it’s connected to the backend. Navigate to http://localhost:3001/register
   - If everything is working properly, you’ll be able to create a new user
