# Pronto PostgreSQL

Docker Compose configuration for PostgreSQL 16.

## Quick Start

```bash
cp .env.example .env
docker-compose up -d
```

## Configuration

Edit `.env` to customize:
- PostgreSQL credentials
- Network settings
- Application settings

## Services

- **PostgreSQL**: `postgres:16-alpine` on port 5432
