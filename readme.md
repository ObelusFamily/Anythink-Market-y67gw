# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

* Install docker on your local machine - you can follow the guide here: https://docs.docker.com/get-docker/
* To verify the installation is successfull please run the following: `docker -v` and `docker-compose -v` and verify you are seing an answer with a version
* Go to the project root directory and run `docker-compose up`, if you are getting error for permmision denied try to open the shell as administrator in Windwos or run `sudo docker-compose up` in Linux/Mac
* After the setup is finished, you can verify that the backend is running flawlessly by running the command: `http://localhost:3000/api/ping`, you should see something like this: `{"msg":"Pong! Seems like Everythink is working, great job!"}`
* To check that the frontend is connected to the backend, please go to `http://localhost:3001/register` and create a new user
