# Pronto PostgreSQL

Docker Compose configuration for PostgreSQL 13.

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

- **PostgreSQL**: `postgres:13-alpine` on port 5432
