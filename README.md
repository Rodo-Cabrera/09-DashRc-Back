# DashRC API: Node.js + TypeScript auth backend

REST API for the [DashRC admin dashboard](https://github.com/Rodo-Cabrera/09-DashRc): user registration and login with hashed passwords and JWT.

## Features

- `auth` routes for registration, login and token revalidation.
- Passwords hashed with bcrypt; JWTs signed and verified with a revalidation middleware.
- Request validation with express-validator.
- MySQL persistence with TypeORM entities.
- Dockerfile for containerized deploys.

## Tech stack

Node.js · Express · TypeScript · TypeORM · MySQL · JWT · bcryptjs · express-validator · Docker

## Getting started

```bash
npm install
cp .env.example .env   # DB connection, JWT_SECRET and PORT
npm run dev        # nodemon + ts-node
npm run build && npm start
```

## Author

**Rodolfo Cabrera**: Full Stack & Mobile Developer. [GitHub](https://github.com/Rodo-Cabrera)
