# Examen de certification : Concevoir une base de données

Cet examen est  nécessaire à l'évaluation de votre aptitude à passer la certification et ses résultats sont demandés par l'institution l'organisant.

Le but de cet examen est de vous faire répondre à un cahier des charges quant à la création d'une BDD pour une application web. Pour cet exercice, l'application en question permet de faire une recherche cinématographique/série selon plusieurs critères.

Cet examen est à faire en deux étapes, une première modélisation entité/association puis la modélisation physique des données. 

## Contexte
La startup "Cineart" souhaite rivaliser les plateformes numériques actuelles telles que NETFLIX/Plex pour la création d'un media center national dedié au cinema indépendant français. 

Chaque film référencé sur la plateforme affichera l'ensemble des acteurs principaux ainsi que les réalisateurs.
Tout film disposera d'informations propres telles que son nom, son affiche, une date de sortie, un genre, un synopsis.

Il sera possible de noter de 1 à 5 étoiles un film accompagné d'un avis (champ texte < 256 char).  Plusieurs avis existeront pour chaque film. 
Il sera possible de définir de un à plusieurs "tags" pour chaque film.

Il devra également être possible d'accéder aux informations propres des réalisateurs et/ou des acteurs. Les informations concernant ces personnes n'ont pas été définies, une veille concurentielle est à réaliser. 



## Production attendue

Le rendu sera à faire sous la forme d'un document word dans lequel apparaîtra :

- Un dictionnaire de données
- Schéma entité/association (à réaliser de façon manuscrite ou avec un outil)
- Schéma physique de la base de données

L'ensemble des données devra être stocké au sein d'une base de données relationnelle (modèle entité/Association). 
Une fois cette modélisation réalisée, vous devez réaliser le **schéma physique des données** en suivant les principes du _modèle relationnel_. Ce document sera à incorporer au dossier initial.

Selon le REAC, il vous est demandé que : 

- Le schéma entité association couvre les règles de gestion sur les données.
- Le schéma respecte le formalisme du modèle entité/association.
- Le schéma physique de la base de données est normalisé.
