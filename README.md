# SAE501

Application web full-stack — plateforme de gestion entre associations et mairie.

## Stack

- **Frontend** — Next.js 16, TypeScript, Tailwind CSS
- **Backend** — Symfony 7.4 LTS, API Platform, FrankenPHP
- **Base de données** — MongoDB 7
- **Serveur** — FrankenPHP (Caddy intégré, HTTPS automatique)
- **Infrastructure** — Docker, GitHub Actions CI/CD

## Démarrage rapide

### Prérequis
- Docker + Docker Compose

### Installation

```bash
git clone git@github.com:wgader/SAE501.git
cd SAE501
cp .env.example .env  # remplir les valeurs
docker compose up --build
```

- Frontend → http://localhost:3000  
- Backend  → http://localhost:80

## Structure

├── frontend/ # Next.js
├── backend/ # Symfony
├── docker/ # Dockerfiles et config serveur
└── .github/workflows/ # CI/CD


## Équipe

Wahel Gader
Vivien Pain
Suzanne Kamara
Manon Lippler
