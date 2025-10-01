
# 📋 TO DO LIST (Front)

![React](https://img.shields.io/badge/React-black) ![MIT](https://img.shields.io/badge/License-MIT-pink)


## 📝 Description

**Todo list** est une application web simple permettant à un utilisateur de consulter sa todo list, ajouter ou supprimer des todos.
Ce projet est couplé avec une API qui récupère les todos dans une base de données, Le frontend a donc besoin de l'API pour fonctionner correctement`https://github.com/Zitoone/todo-back`


## 📂 Structure du projet

```
src/
    components/      # Composants réutilisables (AddElement, Element)
    pages/           # Pages principales de l'application (TodoPage.jsx)
    App.jsx          # Point d’entrée de l’application React
```

## ⚙️ Installation

### Prérequis

- Node.js (version 24 ou supérieure)
- npm 

### Etapes

1. Cloner le repo du front
```bash
git clone https://github.com/Zitoone/todo-front
```

2. Installer les dépendances
```bash
npm install
```

3. Lancer le frontend
```bash
npm run dev
```

L'application est disponible sur [http://localhost:5173]


## 📊 Fonctionnalités principales

* Affichage de la liste des todos depuis l’API

* Ajouter un todo via un champ texte

* Cocher/décocher un todo lorsqu’il est complété

* Supprimer un todo de la liste


## 🔧 Scripts disponibles

npm run dev          # Lance le serveur de développement
npm run build        # Construit l'application pour la production
npm run preview      # Prévisualise la build de production


## 🚀 Déploiement

**Important** Déployer le backend d'abord!

### Etapes

1. Déployer le backend (voir README du projet [todo-back](https://github.com/Zitoone/todo-back))  
→ exemple de déploiement : [Render](https://render.com) et récupérer l’URL du backend déployé (exemple : `https://todo-back-6kzw.onrender.com`).

2. Déployer le front avec Vercel (Créer un compte si besoin [Vercel](https://vercel.com/) et connecter le à votre compte Github)
- Installer Vercel sur le projet front
```bash
npx vercel
```
- Connecter le projet à votre compte Vercel
```bash
npx vercel login
```
→ Suivre les étapes, une connexion au repository se fait.
Lorsque l'installation vous demande d'ajouter les variables d'environnement, n'oubliez pas d'indiquer à Vercel la connection avec l'API.
(exemple: `VITE_APP_API_URL=https://todo-back-6kzw.onrender.com/api/v1`)

_Les variables d'environnement peut être renseignées également une fois le déploiement effectué via le **dashboard** de l'application sur Vercel, dans la section **Settings**, puis **Environnement Variables**_

3. Configuration des variables d'environnement dans le dossier frontend

Créer un fichier `.env` à la racine :

```env
VITE_APP_API_URL=https://todo-back-6kzw.onrender.com/
```

5. Le frontend est alors disponible en ligne à l’URL fournie par Vercel 🚀


## 🤝 Contribution

1. Fork le projet
2. Créez une branche pour votre fonctionnalité (`git checkout -b feature/AmazingFeature`)
3. Committez vos changements (`git commit -m 'Add some AmazingFeature'`)
4. Push vers la branche (`git push origin feature/AmazingFeature`)
5. Ouvrez une Pull Request

## 📝 Licence

Ce projet est réalisé dans le cadre du parcours _Développeur Web & web mobile_ de La Plateforme est en license MIT.

## 🦄 Auteur

Projet réalisé par Olivia Nanquette dans le cadre du parcours _Développeur Web & web mobile_

