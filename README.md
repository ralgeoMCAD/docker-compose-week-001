# IDM 6630 Week 1 Docker Compose Repo
## A small repo for use in MCAD's Spring 2018 section of IDM 6630

To use this repo for local PHP development, do the following:

* Download, clone or fork this repo onto your local development computer. You should be able to save the repo anywhere on your computer, but do keep in mind that saving repos in folders like your Dropbox folder, (or other similar file sync services), can sometimes cause problems with your Git commits and file histories.
* Install [Docker](https://www.docker.com/) on your local development computer.
* Make sure Docker is running on your system.
* In your command line interface application, (CLI), navigate to the repo folder.
* From there run the following command in your CLI application: `docker-compose up`.
* You should see output in your CLI indicating that Docker is starting to build the container. If you are running the container for the first time, you may have to wait several minutes while Docker downloads all of the necessary files and dependencies needed to run the container.
* Once the Docker container has finished loading and is running, visit the following URL in your web browser: `localhost:8080`. You should see the code/index.php file returning correctly in browser.
* Once you are done your development, you can stop the Docker container by entering the CTRL-C command in your CLI application.
