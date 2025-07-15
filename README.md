# 📝 Task Manager - MERN Stack "Application-Task-Management-MERN "

Une application de gestion de tâches complète construite avec la pile **MERN** (MongoDB, Express.js, React, Node.js). 
Les utilisateurs peuvent s'inscrire, se connecter, créer des listes de tâches, fixer des échéances, et suivre leur progression.
![A MERN application for basic tasks management.](image/USERIMAGE.png)

---

## 🚀 Démo

- Frontend (Vercel) : [(https://vercel.com/malaks-projects)](https://vercel.com/malaks-projects-55ad8473/application-task-manager-mern)


## 🛠️ Technologies utilisées

- **Frontend** : React, Axios, React Router
- **Backend** : Express.js, Node.js, JWT, MongoDB
- **Base de données** : MongoDB Atlas
- **Déploiement** : Vercel (Frontend), Render (Backend)

---

## 📦 Fonctionnalités

- 🔐 Authentification avec JWT (inscription / connexion)
- ✅ Création, modification et suppression de tâches
- 📆 Gestion des échéances
- 📊 Suivi de progression (tâches complétées / non complétées)
- 👤 Dashboard utilisateur personnalisé
- 🌐 API REST sécurisée

---

## 📁 Arborescence du projet

/Application-Task-Management-MERN
├── client/ # React frontend
├── server/ # Node.js + Express backend
├── README.md

## ⚙️ Installation en local

### 1. Clone le projet

```bash
git clone https://github.com/malakmedfai/Application-Task-Management-MERN.git

cd mern-task-**manager**

2. Backend (Express.js)
cd server
npm install

Crée un fichier .env :
mongodb+srv://medfaimalak:07976923malak@cluster0.lidiuut.mongodb.net/MERN-task-manage?retryWrites=true&w=majority&MERN-task-manage=Cluster0
MONGODB_URL=mongodb://localhost:27017/MERN-task-manager
PORT=5000

Lance le serveur :
node server.js

3. Frontend (React)
cd ../client
npm install

Crée un fichier .env :
REACT_APP_API_URL=http://localhost:5000

Lance le client React :
npm start

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
