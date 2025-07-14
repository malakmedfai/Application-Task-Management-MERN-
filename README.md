📚 Gestionnaire de Tâches - Stack MERN

🔖 Table des matières

Fonctionnalités
Outils et technologies
Dépendances
Dépendances de développement

Prérequis
Installation et configuration
API backend
Pages frontend
Scripts npm
Liens utiles
Contact

✅ Fonctionnalités

👤 Côté utilisateur :
Inscription
Connexion
Déconnexion
Ajouter des tâches
Afficher les tâches
Mettre à jour les tâches
Supprimer des tâches

👨‍💻 Côté développeur :

Affichage de messages de succès et d'erreur (toasts)
Validation des formulaires côté client et serveur
Barre de navigation responsive
Authentification via JWT (JSON Web Token)
Page 404 pour les URL non valides
Redirections pertinentes selon l’état utilisateur
État utilisateur global géré avec Redux
Loaders personnalisés
Composant de mise en page (Layout) pour structurer les pages
Utilisation d’un thème de couleurs via Tailwind CSS
Aucune feuille CSS externe nécessaire
Info-bulles (Tooltips) pour plus de clarté
Titres de pages dynamiques
Redirection vers la dernière page après connexion
Utilisation de hooks React natifs et personnalisés (useFetch)
Protection des routes privées
Middleware backend pour vérification des utilisateurs
Réponses API avec des codes HTTP appropriés
Bonnes pratiques de développement respectées

🛠️ Outils et technologies
HTML
CSS
JavaScript
Tailwind CSS
Node.js
Express.js
React
Redux
MongoDB

📦 Dépendances principales
bash
Copier
Modifier
axios
react
react-dom
react-redux
react-router-dom
react-toastify
redux
redux-thunk
bcrypt
cors
dotenv
express
jsonwebtoken
mongoose

🧪 Dépendances de développement
bash
Copier
Modifier
nodemon
concurrently (pour exécuter frontend + backend en même temps)

🧰 Prérequis
Node.js installé sur le système
Une base de données MongoDB (locale ou via MongoDB Atlas)
Un éditeur de code (recommandé : VS Code)

⚙️ Installation et configuration
Installer toutes les dépendances du projet (frontend + backend) :

bash
Copier
Modifier
npm run install-all
Créer un fichier .env dans le dossier backend :
Copie le contenu de .env.example
Renseigne :
MONGO_URI
JWT_SECRET
PORT (facultatif)

Démarrer le projet (backend + frontend) :
bash
Copier
Modifier
npm run dev
Ouvrir le navigateur à l’adresse :
arduino
Copier
Modifier
http://localhost:3000

🔌 API Backend
Méthode	Route	Description
POST	/api/auth/signup	Créer un compte utilisateur
POST	/api/auth/login	Connexion utilisateur
GET	/api/tasks	Récupérer toutes les tâches
GET	/api/tasks/:taskId	Récupérer une tâche spécifique
POST	/api/tasks	Ajouter une tâche
PUT	/api/tasks/:taskId	Mettre à jour une tâche
DELETE	/api/tasks/:taskId	Supprimer une tâche
GET	/api/profile	Obtenir le profil utilisateur

🌐 Pages Frontend
URL	Fonction
/	Page d’accueil (publique ou tableau des tâches privé)
/signup	Page d'inscription
/login	Page de connexion
/tasks/add	Formulaire d'ajout d’une tâche
/tasks/:taskId	Modifier une tâche existante

📜 Scripts npm
À la racine du projet :
bash
Copier
Modifier
npm run dev           # Lance backend + frontend ensemble
npm run dev-server    # Lance uniquement le backend
npm run dev-client    # Lance uniquement le frontend
npm run install-all   # Installe toutes les dépendances des 3 parties
Dans le dossier frontend/ :
bash
Copier
Modifier
npm start             # Démarrage du frontend en mode développement
npm run build         # Construction du frontend pour la production
npm test              # Lancement des tests React
npm run eject         # Éjecte le projet de Create React App (non réversible)
Dans le dossier backend/ :
bash
Copier
Modifier
npm run dev           # Lance le backend avec nodemon (hot reload)
npm start 
