RAMOUL Racha
BIRABOURAME Hemavathi

# Symfony 6 + PHP 8.0.13 with Docker

## Run Locally

Clone the project

Run the docker-compose

```bash
  docker-compose build
  docker-compose up -d
```

Log into the PHP container

```bash
  docker exec -it php8-sf6 bash
```

Go to Symfony application launch the internal server

```bash
  cd todo_project
  symfony serve -d
```

_application is available at http://127.0.0.1:9000/task_
