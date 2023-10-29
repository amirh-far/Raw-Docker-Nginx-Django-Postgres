# Raw-Project-for-Docker-Nginx-Django-Postgres

This repository is a raw project template for Nginx, Django, Daphne, Postgres composed with Docker

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Preview](#preview)

## Features

- Uses Revese Proxy with Nginx 
- Fully functional with Django
- Supports sockets because Runs the server with Daphne ASGI
- Uses Postgres Database Management which is a popular choice
  
## Installation

First off install Docker on your machine: [install docker](https://www.docker.com/products/docker-desktop/)

Clone the repository:

```bash
# Clone the repository
git clone https://github.com/your-username/your-project.git
```

Use docker compose to create the containers, compose them and run the server:
```
sudo docker compose up
```
## Preview

After installation you should see the following page with 0.0.0.0 url using these ports: <br>
Http Ports:<br>
80,8080,8880,2052,2082,2086,2095<br>
Https Ports:<br>
443,2053,2083,2087,2096,8443<br>

<img src="https://github.com/amirh-far/Raw-Project-4-Docker-Nginx-Django-Postgres/blob/main/Readme.md%20images/Screenshot%201402-08-07%20at%201.43.58%20in%20the%20afternoon.png"/>
You are ready to go!
