# Return Tracker

Return Tracker est une petite application Flask permettant de suivre les retours produits d'une boutique en ligne.

L'objectif du projet est de centraliser les produits, d'enregistrer les retours clients et de garder une trace des infos liées à chaque retour.

## Version 1 - Suivi simple des retours

Cette première version contient les fonctionnalités essentielles :

- import de produits depuis un fichier CSV Shopify ;
- ajout manuel d'un produit ;
- modification et suppression d'un produit ;
- enregistrement d'un retour produit;
- consultation de la liste des retours enregistrés.

## Utilité

L'objectif de cette V1 est de poser une base simple et fonctionnelle avant d'ajouter des analyses plus avancées.

À ce stade, l'application permet déjà de répondre au besoin principal : savoir quels produits ont été retournés, pour quelle raison, et quelle action a été prise.

## Technologies utilisées

- Python
- Flask
- HTML
- CSS
- CSV


## Lancer le projet

Depuis le dossier du projet, créer un environnement virtuel :

python3 -m venv venv

Activer l'environnement virtuel :

source venv/bin/activate

Installer les dépendances :

pip install -r requirements.txt

Lancer l'application :

python app.py

Ouvrir ensuite l'application dans le navigateur :

http://127.0.0.1:5050
Fichiers de données

Les données sont stockées dans des fichiers CSV dans le dossier data.

Le fichier products.csv contient les produits importés ou ajoutés manuellement.

Le fichier returns.csv contient les retours enregistrés depuis l'application.

Évolution prévue

La prochaine version ajoutera une page de statistiques opur d'identifier les produits les plus retournés et les raisons de retour les plus fréquentes