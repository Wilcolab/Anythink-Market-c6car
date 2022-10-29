# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_
# -Anythink-Market-c6car

-Install Docker from the official Docker website https://docs.docker.com/get-docker/
-Confirm Docker installation using docker -v to displat the version of installed docker.
-If Docker is working correctly, the backend should be running and able to connect to your local database. This can be done by going to http://localhost:3000/api/ping on your browser.
-Run docker-compose up from the root directory
-Now, it’s time to check the frontend and make sure it’s connected to the backend. If everything is working properly, you’ll be able to create a new user on http://localhost:300

