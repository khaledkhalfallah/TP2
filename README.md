Cette API REST, développée avec Node.js, Express.js et SQLite, permet de gérer un registre de personnes (ajout, consultation, modification, suppression).
La sécurité des accès est assurée via Keycloak avec le protocole OAuth 2.0.

Fonctionnalités
Opérations CRUD sur les personnes

Authentification et autorisation avec Keycloak

Stockage local des données en SQLite

Test via Postman ou tout client HTTP

Structure du projet
index.js : Serveur Express

database.js : Configuration de SQLite

keycloak-config.json : Paramètres Keycloak

package.json : Dépendances

README.md : Documentation

Installation
Installer les dépendances :

bash
Copier
Modifier
npm install
Supprimer l’ancienne base si nécessaire :

bash
Copier
Modifier
rm maBaseDeDonnees.sqlite
Lancer le serveur :

bash
Copier
Modifier
node index.js
API disponible sur http://localhost:3000
