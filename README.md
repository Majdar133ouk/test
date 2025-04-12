# 📋 Fullstack Application - User Management System

Ce projet est une application **Fullstack** construite avec **React (frontend)** et **Express.js (backend)** permettant la **gestion des utilisateurs**.  
Elle permet d’effectuer les opérations suivantes :

- ➕ Ajouter un utilisateur
- ✏️ Modifier un utilisateur
- ❌ Supprimer un utilisateur
- 📄 Lister tous les utilisateurs

---

## 🗂️ Structure du projet

/backend -> Serveur Express.js (API REST) ├── controllers/ ├── routes/ ├── db.js ├── .env ├── dockerfile ├── index.js ├── package.json

/frontend -> Application React.js ├── public/ ├── src/ ├── Dockerfile ├── package.json

.github/ └── node.yml -> Fichier de configuration GitHub Actions

docker-compose.yml


---

## 🚀 Démarrage du projet

Assurez-vous d'avoir **Node.js** installé.

### 🔧 Installation


# Dans le dossier backend
cd backend
npm install

# Dans le dossier frontend
cd ../frontend
npm install
# Lancer le backend
cd backend
npm start
# Le backend démarre sur le port : http://localhost:5001

# Lancer le frontend
cd ../frontend
npm start
# Le frontend est accessible sur : http://localhost:44860


Technologies utilisées

    Frontend: React.js

    Backend: Express.js, Node.js
    
    Docker: Pour conteneuriser l'application

    GitHub Actions: Pour CI/CD

