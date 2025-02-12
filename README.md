# Backend API pour la Gestion des Produits  

Ce projet est une API RESTful construite avec **Node.js**, **Express**, et **MongoDB** utilisant **Mongoose** pour la gestion des produits.  

## Fonctionnalités  
- Création d'un produit (`POST /api/products`)  
- Récupération de tous les produits (`GET /api/products`)  
- Récupération d'un produit par ID (`GET /api/products/:id`)  
- Mise à jour d'un produit (`PUT /api/products/:id`)  
- Suppression d'un produit (`DELETE /api/products/:id`)  

## Prérequis  
- [Node.js](https://nodejs.org/) (version 14.x ou supérieure)  
- [MongoDB](https://www.mongodb.com/) (MongoDB Atlas ou installation locale)  

## Installation  
1. Clonez le dépôt :  
    ```bash
    git clone https://github.com/votre-utilisateur/nom-du-repo.git
    cd nom-du-repo
    ```

2. Installez les dépendances :  
    ```bash
    npm install
    ```

3. Configurez la connexion à MongoDB :   
   - Mettez à jour l'URI de MongoDB :  
     ```
     MONGO_URI=mongodb+srv://<nom_utilisateur>:<mot_de_passe>@backenddb.umvzd.mongodb.net/BackendDB?retryWrites=true&w=majority
     ```

## Utilisation  
Pour démarrer le serveur en mode développement avec **nodemon** :  
```bash
npm run dev
