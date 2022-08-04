# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

Step 1 : install docker ( check docker documentation for more info )
Step 2 : verify if installed or not using these two commands -> ```docker -v``` and ```docker-compose -v```
Step 3 : Then, run ```docker-compose up``` from the project root directory to load Anythink's backend and frontend.
Step 4 : Let's test this by pointing your browser to http://localhost:3000/api/ping
Step 5 : If everything is working properly, you’ll be able to create a new user on http://localhost:3001/register
Step 6 : Create a new user there with a cool useranme and your initial setup is ready now 😎

