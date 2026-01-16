1. Initialisation du Projet
Crée un dossier pour ton projet :

BASH



mkdir mon-projet-securise
cd mon-projet-securise
mkdir backend
cd backend

Initialise un projet Node.js avec npm/yarn :

BASH



npm init -y
# ou
yarn init -y
Installe les dépendances principales :

BASH



# Langage principal et framework web
npm install express express-validator dotenv

# TypeScript et types
npm install --save-dev typescript ts-node nodemon @types/node @types/express @types/cors @types/bcryptjs @types/jsonwebtoken @types/express-validator

# Base de données (Prisma recommandé pour sa modernité et sécurité)
npm install prisma --save-dev
npm install @prisma/client
# Si tu préfères TypeORM: npm install typeorm reflect-metadata pg
