# docker-flask-demo

A minimal, containerised Python Flask application: a clean example of packaging and running a web app with Docker.

## What it shows
- A small Flask app (`project-1/src/app.py`)
- A single-stage `Dockerfile` on a slim Python base
- Externalised configuration via a gitignored `.env` (see `project-1/config/.env.example`)
- A step-by-step setup guide (`project-1/docs/setup-guide.md`)

## Quick start
```bash
cd project-1
docker build -t project-1 .
docker run -p 5000:5000 project-1
# then visit http://localhost:5000
```

See `project-1/docs/setup-guide.md` for the full walkthrough.
