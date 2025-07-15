# focusme
Très bien ✅ ! Voici comment ajouter ce `README.md` dans ton dépôt GitHub **manuellement ou depuis ton ordinateur** :

---

## 🧠 Option 1 : Modifier en ligne sur GitHub

1. Va dans ton dépôt GitHub (ex. : `https://github.com/ton-utilisateur/focusme`)
2. Clique sur le fichier `README.md` (ou sur “Add a README” s’il n’existe pas)
3. Clique sur le bouton ✏️ **“Edit this file”**
4. Colle tout le contenu ci-dessous 👇 dans la zone d’édition
5. En bas, écris un message de commit :
   `Ajout du README initial`
6. Clique sur **“Commit changes”**

---

## 🧠 Option 2 : Depuis ton ordinateur

1. Dans ton dossier `focusme/`, crée le fichier :

```bash
touch README.md
```

2. Ouvre-le avec ton éditeur de code (VS Code, par exemple)

3. Colle ceci dans le fichier :

```markdown
# 🎯 FocusMe – Application de Suivi d'Objectifs et Apprentissage Personnel

FocusMe est une application web conçue pour aider chaque utilisateur à :
- définir ses objectifs (études, développement personnel, religion…)
- suivre ses tâches (texte, audio, vidéo)
- synthétiser ce qu’il apprend (résumés)
- faire des bilans réguliers
- recevoir des rappels
- progresser de manière autonome et motivée

---

## 🧠 Fonctionnalités clés

- 📌 Création d’objectifs personnalisés
- ✅ Suivi des tâches (avec types : texte, audio, vidéo)
- 🧠 Résumés après chaque tâche ou apprentissage
- 📊 Auto-évaluations régulières
- 📅 Rappels et planning d’apprentissage
- 🔐 Authentification et tableau de bord utilisateur
- 🧑‍💻 Espace personnel évolutif

---

## 🧩 Technologies utilisées

| Partie        | Outils               |
|---------------|----------------------|
| Frontend      | React, Tailwind CSS, Vite |
| Backend       | FastAPI (Python), JWT |
| Base de données | SQLite (local) ou PostgreSQL (production) |
| Déploiement   | GitHub, Render, Docker (plus tard) |

---

## 🗂️ Structure du projet

```

📁 focusme/
├── 📁 backend/                     # API FastAPI (Python)  
│   ├── requirements.txt           # Dépendances backend  
│   └── 📁 app/
│       ├── main.py                # Point d'entrée de l'API  
│       ├── auth.py                # Authentification (JWT)  
│       ├── database.py            # Connexion BDD  
│       ├── models.py              # Modèles SQLAlchemy  
│       ├── schemas.py             # Schémas Pydantic (validation)  
│       └── 📁 routers/            # Routes de l'API  
│           ├── users.py           # CRUD utilisateurs  
│           ├── goals.py           # CRUD objectifs  
│           ├── tasks.py           # CRUD tâches (texte/audio/vidéo)  
│           ├── summaries.py       # Résumés d'apprentissage  
│           └── evaluations.py     # Auto-évaluations  

├── 📁 frontend/                   # Interface React  
│   ├── package.json              # Dépendances JS  
│   ├── tailwind.config.js       # Config Tailwind CSS  
│   ├── postcss.config.js        # PostCSS (styling)  
│   └── 📁 src/
│       ├── App.jsx               # Composant principal  
│       ├── main.jsx              # Point d’entrée React  
│       ├── api.js                # Connexion à l’API backend  
│       ├── 📁 pages/             # Pages de navigation  
│       │   ├── Home.jsx
│       │   ├── Goals.jsx
│       │   ├── Tasks.jsx
│       │   ├── Summary.jsx
│       │   ├── Evaluation.jsx
│       │   ├── Login.jsx
│       │   └── Register.jsx
│       └── 📁 components/        # Composants réutilisables  
│           ├── GoalCard.jsx
│           ├── TaskList.jsx
│           ├── LoginForm.jsx
│           ├── RegisterForm.jsx
│           ├── Navbar.jsx
│           ├── ProtectedRoute.jsx
│           └── Loader.jsx

├── README.md                    # Description du projet  
└── .gitignore                   # Fichiers à ignorer dans Git  


````

---

## 🚀 Installation (développement local)

### Backend (FastAPI)
```bash
cd backend
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
uvicorn app.main:app --reload
````

### Frontend (React)

```bash
cd frontend
npm install
npm run dev
```

---

## 🔐 Authentification

* Les utilisateurs peuvent s’inscrire et se connecter
* Le token JWT est utilisé pour sécuriser les appels API

---

## 📦 À venir (roadmap)

* 🔔 Notifications de rappel
* 🎯 Gamification des objectifs
* 📱 Version mobile (PWA)
* 🐳 Dockerisation complète

---

## ✍️ Auteur

Développé par **Fatoumata NDOUR**
En cours de développement dans un but personnel et pédagogique 🌱

````