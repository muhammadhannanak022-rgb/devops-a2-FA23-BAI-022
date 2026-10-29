# DevOps Assignment 2 — Personal Portfolio

## Project Overview

This project is a personal portfolio website created using HTML and CSS for the Cloud Computing Lab course.

## Technologies Used

- HTML
- CSS
- Git
- GitHub
- Docker
- Nginx
- GitHub Actions

## Run Locally

Open `index.html` in a web browser to view the website.

## Run with Docker

Build the image:

```bash
docker build -t devops-a2:manual .
```

Run the container:

```bash
docker run -d -p 8080:80 --name page devops-a2:manual
```

Open `http://localhost:8080` in your browser.

## Automation

GitHub Actions checks the website, builds the Docker image, and publishes the `latest` image to Docker Hub when changes are pushed to the main branch.

## Author

Name: YOUR_NAME

Roll Number: YOUR_ROLL_NUMBER