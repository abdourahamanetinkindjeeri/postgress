# PostgreSQL Docker pour Railway

Ce projet permet de déployer une base PostgreSQL personnalisée avec un script d'initialisation.

## 💻 Utilisation locale

1. Lancer la base :

```
docker-compose up --build -d
```

2. Connexion locale :

- Hôte : `localhost`
- Port : `5432`
- Utilisateur / Mot de passe / Base : dans le fichier `.env`

## 🚀 Déploiement Railway

1. Pusher ce projet sur GitHub
2. Aller sur [https://railway.app](https://railway.app)
3. Créer un projet Railway via GitHub
4. Ajouter les variables d’environnement :
   - POSTGRES_DB
   - POSTGRES_USER
   - POSTGRES_PASSWORD

Railway construira et exécutera PostgreSQL avec les données initiales automatiquement.
