# Langfuse Self-Hosted Setup

This repository contains a self-hosted setup for Langfuse using Docker.

## Prerequisites

* Docker installed
* Docker Compose installed

## Setup

1. Clone the repository:

```bash
git clone <your-repo-url>
cd <your-repo-folder>
```

2. Ensure your `docker-compose.yml` (from official Langfuse docs) is present.

3. Start the services:

```bash
docker compose up -d
```

## Access

Once running, open:

```
http://localhost:3000
```

## Notes

* Update environment variables in `.env` if required.
* Use `docker compose down` to stop services.

---

Simple, quick, and ready to run 🚀
