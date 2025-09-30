
# 📊 TO DO LIST

![React](https://img.shields.io/badge/React-18.2.0-blue)

## 📝 Description

**Todo list** est une application web simple permettant à un utilisateur de consulter sa todo list, ajouter ou supprimer des todos.
Ce projet est couplé avec une API qui récupère les todos dans une base de données lien back


## 📂 Structure du projet

```
src/
  components/   
  pages/            
  App.jsx
```

## ⚙️ Installation

### Prérequis

- Node.js (version 16 ou supérieure)
- npm ou yarn

### 1. Cloner le repo

```bash
git clone https://github.com/Zitoone/todo-front
```

### 2. Installer les dépendances

```bash
npm install
```

### 3. Configuration des variables d'environnement

Créer un fichier `.env` à la racine :

```env
REACT_API_URL=https://todo-back-6kzw.onrender.com/
```


### 4. Lancer le backend (optionnel)

Si vous avez accès au backend Node.js :

- Récupérez le repo backend
- Suivez les instructions d'installation dans le README backend
- Lancez le serveur sur `http://localhost:3000`

### 5. Lancer le frontend

```bash
npm run dev
```

L'application est disponible sur [http://localhost:5173](http://localhost:5173).

## 📊 Fonctionnalités principales




## 📐 Conventions & Documentation

- **PropTypes** pour typer les composants React
- **Mappers** pour transformer les données API en un modèle unique
- **JSDoc** pour documenter les services et fonctions utilitaires
- **CSS Modules** pour la gestion des styles

## 🔧 Scripts disponibles

```bash
npm run dev          # Lance le serveur de développement
npm run build        # Construit l'application pour la production
npm run preview      # Prévisualise la build de production
npm run lint         # Lance ESLint pour vérifier le code
```


## 🚀 Déploiement

Pour déployer l'application :

```bash
npm run build
```

Les fichiers de production seront générés dans le dossier `dist/`.

# Documentation Technique (JSDoc)

Cette documentation est générée automatiquement à partir des commentaires JSDoc présents dans le code (`src/**/*.js|jsx`).

## Générer la documentation

```bash
# Installation (une seule fois)
npm i -D jsdoc jsdoc-to-markdown

# Générer la doc HTML (dans docs/html)
npm run docs:html

# Générer la doc Markdown (docs/api.md)
npm run docs:md


## 🤝 Contribution

1. Fork le projet
2. Créez une branche pour votre fonctionnalité (`git checkout -b feature/AmazingFeature`)
3. Committez vos changements (`git commit -m 'Add some AmazingFeature'`)
4. Push vers la branche (`git push origin feature/AmazingFeature`)
5. Ouvrez une Pull Request

## 📝 Licence

Ce projet est réalisé dans le cadre du parcours _Développeur Web Front End_ d'OpenClassrooms.

## 👤 Auteur

Projet réalisé par Dalila LE dans le cadre du parcours _Développeur Web Front End -- OpenClassrooms_.
```
