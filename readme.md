# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

-Clone the repository (do not fork it)
-Install Docker at https://docs.docker.com/get-docker/
-Test Docker installationg by opening a terminal and typing 'docker -v' and 'docker-compose -v'
    -Each command should return a docker reponse with a version #
-Terminal to the project root and run 'docker-compose up'
-When docker is finished building the container, test communication by opening a browser and browsing to http://localhost:3000/api/ping
-Test frontend and backend communication by going to http://localhost:3001/register and creating a fake account