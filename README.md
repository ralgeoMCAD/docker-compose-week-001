# IDM 6630 Week 1 Docker Compose Repo

## A small repo for use in MCAD's Spring 2018 section of IDM 6630

### To use this repo for local PHP development, do the following:

* __Download all of the code in this repo onto your local development computer__. Please don't clone or fork the repo. You should be able to save the repo anywhere on your computer, but do keep in mind that saving repos in folders that sync with cloud-based file sharing services, (like Dropbox or iCloud), can sometimes cause problems with your Git commits and file histories.
* __Install [Docker](https://www.docker.com/)__ on your local development computer, if you haven't already.
* __Make sure Docker is running on your system__. You can test this by running the command `docker version` in your command line interface application, (CLI).
* __In your CLI, navigate to the repo folder__. The repo folder is where ever you saved the code on your computer.
* From that folder, __run the following command in your CLI application__: `docker-compose up`. You should see output in your CLI indicating that Docker is starting to build the container. If you are creating the container for the first time, you may have to wait several minutes while Docker downloads all of the necessary files and dependencies needed to create and run the container.
* Once the Docker container has finished loading and is running, __visit the following URL in your web browser__: `localhost:8080`. You should see the index.php file from the code folder in the repo being returning correctly in browser. Note that you will also see server logs start to populate the CLI window from which you ran the `docker-compose up` command.
* Proceed with whatever development you need to do by working directly on the files in the repo folder on your computer. Any changes that you make to those files will automatically be synced to the versions running inside the Docker container.

### To stop the docker container

There are a few different ways to stop the Docker container being used to run your web server. You don't have to necessarily stop the container, but it's usually a good idea to do so when you're not using it. Here are the two simplest ways to stop your container:

* If you still have the CLI window with the server logs open and running, just focus on that window and type: `CTRL-C`. That will stop the Docker container automatically.
* If you don't have the CLIE window with the server logs open, (maybe you accidentally closed it or just can't find it...), just open up a new CLI window, navigate to the repo folder and enter the following command: `docker-compose down`. That command will use the docker-compose.yml file to identify the container that should be stopped and stop it for you.
