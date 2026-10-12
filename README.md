# Docker Learning

# Docker Projects

A collection of Docker projects covering containerisation, networking and multi-container applications.

## Flask + Redis Application

Built a simple Flask application connected to Redis using Docker Compose.

The application runs in two containers:
- **Flask** handles HTTP requests and displays the response.
- **Redis** stores and updates a visit counter.

Docker Compose manages both containers and allows them to communicate over a shared network.

### Technologies
Docker · Docker Compose · Python · Flask · Redis

### Running the Application

Clone the repository and open the project folder:

```bash
git clone https://github.com/Shuib97/docker-learning-.git
cd docker-learning-/flask-redis-challenge
```

Start the containers:

```bash
docker compose up --build
```

Open `http://localhost:5000` to view the welcome page.

Visit `http://localhost:5000/count` to see the counter increase with each request.

### What I Worked On

- Writing Dockerfiles to build images
- Running multiple containers with Docker Compose
- Connecting Flask and Redis through Docker networking
- Troubleshooting using container logs and `curl`

