# Flask App with Docker

A simple Flask web application that displays random cat GIFs, containerized with Docker.

## Technologies
- Python
- Flask
- Docker
- Alpine Linux

## Run the project

Build the Docker image:

```bash
docker build -t myfirstapp .
```

Run the container:

```bash
docker run -p 8888:5000 --name myfirstapp myfirstapp
```

Open your browser at [http://localhost:8888](http://localhost:8888).

## Project Structure

```text
.
├── app.py
├── requirements.txt
├── Dockerfile
└── templates/
    └── index.html
```
