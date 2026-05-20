"# api-livresgourmand" 
# API Livres Gourmand 📚🍽️

Projet développé dans le cadre d'un projet académique en programmation informatique.

## Description

API REST développée avec Node.js et Express permettant la gestion d'une bibliothèque de livres culinaires.

Cette application permet :

- Ajouter un livre
- Modifier un livre
- Supprimer un livre
- Afficher tous les livres
- Rechercher un livre
- Gestion des auteurs
- Gestion des catégories
- Base de données MySQL

## Technologies utilisées

- Node.js
- Express.js
- MySQL
- JWT Authentication
- Postman
- JavaScript
- REST API

## Installation

Cloner le projet :

```bash
git clone https://github.com/mehdirebahi30-netizen/api-livresgourmand-final.git
```

Installer les dépendances :

```bash
npm install
```

Créer le fichier :

```bash
.env
```

Exemple :

```env
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=
DB_NAME=api_livresgourmand
PORT=5000
JWT_SECRET=votre_secret
```

Démarrer le serveur :

```bash
npm start
```

Ou :

```bash
npm run dev
```

## Structure du projet

```

api-livresgourmand/
│
├── routes/
├── controllers/
├── middleware/
├── models/
├── config/
├── server.js
├── package.json
└── README.md

```

## API Endpoints

### Livres

GET /livres

POST /livres

PUT /livres/:id

DELETE /livres/:id

## Tests

Les tests API peuvent être réalisés avec :

- Postman

## Auteur

Projet réalisé par :

**Mehdi Rebahi et helmi benzaid**
Étudiant international en Programmation Informatique
Collège André-Grasset – Montréal

## Version

Version actuelle : 1.0

---
Projet éducatif réalisé dans le cadre du DEC Programmation Informatique.
