# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

### ''prequisite is to install docker first on your machine from the docker.com website.''

**First clone the followig repo with** 
```sh
git clone https://github.com/repo.git
```
**Then for the next step move into the project directory**
```sh
cd /project
```
**now to run the following backend and the frontend, use the docker-compose command to create container environments where your following backend nd frontend will be running.**
```sh
docker-compose up
```
## Your output should look something like this in your Docker GUI
![Screenshot](image.png)
## Once your application is locally setup in a container environment, you can run the following command to start the application. Paste this url in your browser "http://localhost:3000"