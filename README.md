# Fullstack FastAPI React

A personal template/fork for building full-stack applications with FastAPI and React.

> This repository is forked from [fastapi/full-stack-fastapi-template](https://github.com/fastapi/full-stack-fastapi-template). Upstream documentation and license remain authoritative for components inherited from that project.

## Personal scope

Use this repository as a starting point for experimenting with a FastAPI backend, React frontend, SQLModel/PostgreSQL persistence, Docker, CI, and deployment automation. Record any personal deviations from upstream in this README or the commit history.

## Quick start

Follow the upstream prerequisites and environment setup first. Then use the repository’s own scripts:

~~~bash
docker compose up -d
~~~

Check the current compose files and environment examples before running. Never commit local secrets or production credentials.

## Before publishing a derived project

- rename the application and update branding
- replace example credentials and secret keys
- review Docker images and exposed ports
- run backend, frontend, and end-to-end tests
- keep the upstream attribution and license notices

## Status

Template/fork for development experiments; not a deployed service by itself.