# Running a rails app on docker container
This is a simple rails app with the intent to show how we can use Docker for development.This example will show the development of a Rails application without ever installing Rails on our machine. This app also features docker-compose a tool we use, for defining and running multi-container Docker applications. With Compose, we use a YAML file to configure the application’s services. Then, with a single command, we can create and start all the services from the configuration.


### Technologies used

- Ruby on Rails
- Docker
- Docker-Compose.yml
- Postgresql

### How to run the application

- Clone the repository to your machine:

  `git clone <repository path>`

- Navigate to your repository directory:

  `cd <project directory>`
  
- Run `docker_compose up` to start the containers

- Run `docker_compose ps` to see the running containers

- Run `app rake db:setup` to start the database

- launch the app at `.localhost:3000`
