# e-shop

Bienvenue sur **e-shop** ! Ce projet est une application de boutique en ligne structurée en deux parties principales : un backend Node.js/Express connecté à MongoDB, et un frontend React.

## Structure du dépôt

- **e-shop-backend/** : Serveur Node.js/Express, gestion API, authentification, stockage MongoDB.
- **e-shop-frontend/** : Interface utilisateur développée avec React (Create React App).

---

## Prérequis

- Node.js (>= 14.x recommandé)
- npm ou yarn
- Un accès à une base MongoDB (MongoDB Atlas par défaut)

---

## Installation

### 1. Cloner le dépôt
```bash
git clone https://github.com/Steph-mss/e-shop.git
cd e-shop
```

### 2. Installer les dépendances

#### Backend
```bash
cd e-shop-backend
npm install
```

#### Frontend
```bash
cd ../e-shop-frontend
npm install
```

---

## Configuration

### Backend

Copiez le fichier `.env-default` en `.env` dans le dossier `e-shop-backend` et adaptez les valeurs si besoin :

```
PORT=8000
TOKEN="ALALALA"
MONGO_URI='mongodb+srv://guest:hykj5udgSsg9jw7L@cluster0.cbcziue.mongodb.net/?retryWrites=true&w=majority&appName=Cluster0'
DB_NAME='le_prenom_cumun_pour_tout_le_groupe'
```

---

## Lancement

### Backend
```bash
cd e-shop-backend
nodemon server.js
# ou
node app.js
```
Le serveur sera accessible sur [http://localhost:8000](http://localhost:8000).

### Frontend
```bash
cd e-shop-frontend
npm start
```
L'application sera accessible sur [http://localhost:3000](http://localhost:3000).

---

## Scripts Utiles (Frontend)

- `npm start` : lance le serveur de développement React
- `npm test` : lance les tests
- `npm run build` : build de production

Pour plus de détails, voir le [README du frontend](e-shop-frontend/README.md).

---

## Technologies utilisées

- **Frontend** : React (Create React App)
- **Backend** : Node.js, Express, MongoDB, JWT pour l'authentification
- **Déploiement** : Compatible avec tout service Node.js/React

---

## Contribution

1. Forkez ce dépôt
2. Créez une branche (`git checkout -b feature/ma-nouvelle-feature`)
3. Commitez vos modifications (`git commit -m 'feat: nouvelle feature'`)
4. Pushez la branche (`git push origin feature/ma-nouvelle-feature`)
5. Ouvrez une Pull Request

---

## Licence

Ce projet est sous licence MIT.

---

Pour toute question ou bug, merci d’ouvrir une issue ou de contacter le mainteneur du projet.

Bon développement & bon shopping avec **e-shop** !
