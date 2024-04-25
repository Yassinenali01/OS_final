

This project was a great learning experience in using Docker and Docker Compose to create a multi-container application. 

## What I Learned

- **Docker Basics**: I learned how to create Dockerfiles for different services, how to build Docker images, and how to run containers from these images.

- **Docker Compose**: I learned how to use Docker Compose to define multi-container applications, and how to use the `docker-compose up` command to start all the services defined in a `docker-compose.yml` file.

- **Networking in Docker**: I learned how to use Docker's networking features to allow containers to communicate with each other. In this project, I used Docker Compose's default networking to allow the `node-service` service to connect to the `db` service.

- **Volumes in Docker**: I learned how to use Docker volumes to persist data across container restarts. In this project, I used a volume to persist the data of the MariaDB database.

- **Environment Variables in Docker**: I learned how to use environment variables in Docker and Docker Compose to configure the behavior of my application. In this project, I used an `variables.env` file to store the database connection details.

## Achievements

- I successfully created a multi-container application with a Node.js service, an Nginx service, and a MariaDB database service.

- I managed to scale the Node.js service to three instances and used Nginx as a reverse proxy to route requests to these instances.

- I managed to persist the data of the MariaDB database using a Docker volume.

- I managed to use environment variables to configure the database connection details in a secure way.

Overall, this project was a great opportunity to learn about Docker and Docker Compose, and I'm looking forward to using these tools in future projects.