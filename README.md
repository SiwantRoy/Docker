# Multi-Tier Web Application with Docker

This project demonstrates the deployment of a multi-tier web application using Docker. It consists of a front-end web server, a back-end application server, and a MongoDB database, all containerized and orchestrated using Docker Compose.

## Components

- Front-End (Nginx)**: Nginx is used as the front-end web server to serve static content.
- Back-End (Node.js/Express)**: Node.js with Express is used as the back-end application server to handle API requests.
- Database (MongoDB)**: MongoDB is used as the database server to store and manage data.

## Usage

To run the multi-tier web application locally, make sure you have Docker installed on your system. Then, navigate to the project directory and run the following command:

```bash
docker-compose up --build
