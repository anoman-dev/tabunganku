# Tabunganku

A full-stack monorepo for a "Tabungan Berhadiah" savings app with backend (Node.js/Express/Sequelize/PostgreSQL) and frontend (React/TailwindCSS), including Docker support.

## Features
- Backend: RESTful API with authentication, user management, transaction logic (Node.js, Express, Sequelize, PostgreSQL)
- Frontend: Modern UI with React and TailwindCSS
- Docker & docker-compose for easy development and production setup
- Seeders and scripts for development data

## Quick Start

```bash
git clone https://github.com/anoman-dev/tabunganku.git
cd tabunganku
docker-compose up --build
```

Access frontend at http://localhost:3000 and backend at http://localhost:4000

## Folder Structure
- `/backend`: Node.js API
- `/frontend`: React app
- `/seeders`: DB seed/data scripts
- `/scripts`: Utility scripts

## License
MIT
