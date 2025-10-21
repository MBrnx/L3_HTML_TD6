<h1>TD6 CREATION D’API AVEC NODE.JS</h1>

## Installation
1. Cloner le projet
2. Installer les dépendances si elles ne sont pas installées :
```bash
npm install express dotenv
```
```bash
npm install -D typescript ts-node @types/node @types/express nodemon
```
<br>

## Lancement 
Pour le lancement du projet, il suffit de rentrer cette commande : 
```bash
npm run dev
```
Pour voir si le serveur est bien fonctionnel, on peut accéder au lien : 
http://localhost:4000/users 

<br> 

Pour voir la liste des utilisateurs, on tape : 
```bash
curl -X GET http://localhost:4000/users
```
Pour s'enregistrer, on fait : 
```bash
curl -X POST http://localhost:4000/users -H "Content-Type: application/json" -d '{"name": "nom", "email": "nom@example.com"}'
```
Une fois fait, on peut réafficher la liste des utilisateurs, et normalement, notre nom et email apparait. 
