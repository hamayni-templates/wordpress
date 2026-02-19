# WordPress — Hamayni Certified Template

## Description
WordPress est le CMS le plus utilisé au monde. Ce template inclut WordPress + MySQL 8.0, prêt à déployer via Hamayni.

## Prérequis
- Docker & Docker Compose

## Variables d'environnement
| Variable | Requis | Description | Défaut |
|----------|--------|-------------|--------|
| MYSQL_DATABASE | Non | Nom de la base | wordpress |
| MYSQL_USER | Non | Utilisateur MySQL | wordpress |
| MYSQL_PASSWORD | **Oui** | Mot de passe MySQL | — |
| MYSQL_ROOT_PASSWORD | **Oui** | Mot de passe root | — |

## Déploiement
```bash
docker-compose up -d
```

WordPress sera accessible sur le port **8080**.

## Health Check
- URL: `http://localhost:8080`
- Timeout: 60s

## Licence
GPL v2 — WordPress Foundation
