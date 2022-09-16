# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_



Before we dive into the code, we need Docker. It’s going to make it easier for us to run things locally, which we’ll have to do a lot during your work here.
4:52
So first thing’s first - install Docker.
4:52
Write me back when you're done. K?

max westerdahl

4:53 PM
done

Ness

4:53 PM
Great! You can verify docker is ready by running the following commands in your terminal: docker -v and docker-compose -v.
4:53
Then, run docker-compose up from the project root directory to load Anythink's backend and frontend.
4:53
Ok. That’s a great first step - now we can make sure that the code is working :)
4:53
If Docker is working correctly, the backend should be running and able to connect to your local database.
4:53
Let's test this by pointing your browser to http://localhost:3000/api/ping
4:56
Easy Peasy! The backend is up and running.
4:56
Now, it’s time to check the frontend and make sure it’s connected to the backend.
4:56
If everything is working properly, you’ll be able to create a new user on http://localhost:3001/register
4:56
Create one (choose a cool nickname and everything) and you’ll be able to move to the next task.
4:58
Ooohh, I didn’t expect you to do this so quickly! Even your username, coolnick, brings back memories. Strangely enough, they’re your memories, which I don’t know why I have.
4:58
Never mind that, though—you’re done with this dib.
4:58
Just make sure that you run all scripts in the next quests on one of the containers created by docker-compose up.  Also, you can use docker exec to run commands on a running container.
4:58
It looks like your environment is ready! 😀
4:58
To make this process easier for future employees, lets update the readme file and add instructions for setting up a local environment like you just did, and submit a PR.