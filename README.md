# Pharma E-Commerce

This repository contains a full-stack pharmaceutical e-commerce application with a Next.js frontend and Flask backend.

Quick start (development):

1. Copy `.env.example` to `.env` and adjust values.
2. Start services with Docker Compose:

```bash
docker compose up --build
```

3. Backend API: http://localhost:5000/api
4. Frontend: http://localhost:3000

Run backend tests locally:

```bash
cd backend
pytest -q
```
