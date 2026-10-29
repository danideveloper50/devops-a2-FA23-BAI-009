# devops-a2-FA23-BAI-009

Personal portfolio page for **DevOps for Cloud Computing — Assignment 2**.

**Student:** Muhammad Daniyal
**Roll No:** FA23-BAI-009
**Instructor:** Sir Babar Shahzad

## What this project does

A simple static portfolio page (plain HTML + CSS) that is version-controlled
with Git/GitHub, packaged as a Docker image using nginx, and automatically
checked and published to Docker Hub by a GitHub Actions workflow on every push
to `main`.

## Tech

- HTML + CSS (`index.html`, `style.css`)
- Docker (`nginx:alpine` base image)
- GitHub Actions CI (`.github/workflows/ci.yml`)

## Run locally with Docker

```bash
docker build -t daniyalai313/devops-a2:manual .
docker run -d -p 8080:80 --name page daniyalai313/devops-a2:manual
```

Then open http://localhost:8080

## Links

- Docker Hub: https://hub.docker.com/r/daniyalai313/devops-a2
- GitHub: https://github.com/danideveloper50
