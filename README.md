# 📋 Application MERN de Gestion de Tâches "Application-Task-Management-MERN"

Une application de gestion de tâches complète construite avec la pile **MERN** : MongoDB, Express.js, React.js et Node.js.
![A MERN application for basic tasks management.](image/USERIMAGE.png)

## ✨ Fonctionnalités

- 🔐 Authentification sécurisée (JWT)
- ➕ Création de tâches avec titre, description, échéance et statut
- 📝 Mise à jour & suppression des tâches
- 📆 Suivi de l’état : en attente, en cours, terminé
- 🔍 Filtrage et tri des tâches
- 📱 Interface responsive et fluide (React)

---

## ⚙️ Technologies utilisées

- **Frontend** : React, Axios, React Router
- **Backend** : Node.js, Express, MongoDB, Mongoose
- **Authentification** : JWT, bcryptjs
- **Déploiement** : Vercel (frontend), Render/Heroku (backend), MongoDB Atlas (base de données)

---

## 🚀 Installation locale

###  Cloner le dépôt
```bash

git clone https://github.com/malakmedfai/Application-Task-Management-MERN.git
cd Application-Task-Manager-MERN
---
###   Backend

1. Lancer Backend

cd backend
npm install

2. Crée un fichier .env :
Env 
mongodb+srv://medfaimalak:07976923malak@cluster0.lidiuut.mongodb.net/MERN-task-manage?retryWrites=true&w=majority&MERN-task-manage=Cluster0
MONGODB_URL=mongodb://localhost:27017/MERN-task-manager
PORT=5000

3. Lancer le server :
npm run dev

### Frontend

1. Lancer Frontend
cd ../frontend
npm install
npm start
---


##🧪 Tester l’API


📫 POST /api/users/register → Inscription

🔑 POST /api/users/login → Connexion (renvoie un token)

✅ GET /api/tasks → Récupère les tâches de l’utilisateur

➕ POST /api/tasks → Crée une nouvelle tâche

✏️ PUT /api/tasks/:id → Met à jour une tâche

❌ DELETE /api/tasks/:id → Supprime une tâche

🌍 Déploiement

📤 Backend (Render)
Créer un nouveau Web Service

Ajouter les variables d'environnement MONGO_URI et JWT_SECRET

Start command : node server.js

🌐 Frontend (Vercel)
Importer le projet depuis GitHub

Répertoire : client

Build : npm run build

Output : build

Ajouter REACT_APP_API_URL pointant vers le backend Render

## 🚀 Démo

- Frontend (Vercel) :[https://vercel.com/malaks-projects](https://vercel.com/malaks-projects-55ad8473/application-task-manager-mern)

- Backend (Render/Railway) 

---

🧑‍💻 Auteur
Ton Nom
📫 Contact :medfaimalak@yahoo.com
🔗 GitHub : @(https://github.com/malakmedfai)