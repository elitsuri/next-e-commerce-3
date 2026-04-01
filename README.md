# next-e-commerce

> Next E-Commerce: Next.js storefront with SSR, product pages, cart, and payments

## ✨ Features
- JWT authentication with access + refresh tokens
- Role-based access control (admin/user)
- Full CRUD with pagination, search, and filtering
- Premium responsive UI with dark/light mode
- Real-time validation and error handling
- Docker Compose for one-command startup
- Comprehensive README with API documentation
- Database migrations with Alembic/Flyway

## 🧰 Tech Stack
Next.js, TypeScript, GraphQL, PostgreSQL, Apollo

## 🏗️ Architecture
Three-tier architecture: Next.js, TypeScript backend, React/TypeScript frontend, PostgreSQL database. Containerized with Docker.

## 🚀 Quick Start

### Prerequisites
- Docker & Docker Compose
- SQLite / PostgreSQL

### Setup

```bash
# Clone the repository
git clone https://github.com/elitsuri/next-e-commerce
cd next-e-commerce

# Copy environment variables
cp .env.example .env
```

### Run

```bash
docker compose up --build
```
