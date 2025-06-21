# CI/CD Flask App

A sample project to demonstrate CI/CD using GitHub Actions, Docker, and EC2.

## Tech Stack
- Python + Flask
- Docker
- GitHub Actions
- EC2 (or Render)

## Features
- Automated build & test pipeline
- Docker-based deployment
- CI/CD triggered on push to `main`

## Setup
1. Clone repo
2. Run locally:
```bash
docker build -t flask-app .
docker run -p 5000:5000 flask-app
```

3. Visit `http://localhost:5000`

## License
MIT
