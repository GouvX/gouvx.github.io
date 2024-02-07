# Site gouvx.fr

Code de l'interface web de [gouvx.fr](https://www.gouvx.fr/)

## Déploiement

Le branche main est automatiquement déployée sur [gouvx.fr](https://www.gouvx.fr/) avec GitHub pages

## Détails d'implémentation

L'interface web est une page statique html/css/js basée sur bootstrap. L'url de l'API est spécifié en début de fichier dans chatbot.js

L'historique de conversation doit être passé en paramètre en respectant la convention de nommage de openai 

Pour l'instant il n'y a pas de limite sur la taille des conversation, mais il y a une limite à ma carte de crédit