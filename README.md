# EDT MMI
Code source de bot Discord permettant de fournir l'emploi du temps des étudiants en MMI à Mulhouse !

## Installation

Installer la version LTS de NodeJS : https://nodejs.org/fr/download/

Installer les dépendances :
```
npm install
```

Créer un bot discord et obtenir son token : https://discord.com/developers/applications \
Pour fonctionner correctement, le bot doit pouvoir :
- Créer des commandes
- Envoyer des messages

Créer le fichier `config/token.json` et ajouter ceci à l'intérieur :
```
{
  "token": "TOKEN-DU-BOT-DISCORD"
}
```

Démarrer le bot avec la commande :
```
npm start
```

## Utilisation
```
/edt <groupe> <date>
```

## TO DO
- Notification régulière de l'emploi du temps
