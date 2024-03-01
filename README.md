Mini projet Web sémantique
============================

# Description
Pour ce mini-projet axé sur le Web sémantique, je propose de développer une application qui recueille des données sur des films, les modélise en RDF(S), permet aux utilisateurs de rechercher et de filtrer les films selon différents critères, et fournit des informations détaillées sur chaque film.

# Structure de projet
- app : code source de l'application en HTML+JavaScript+CSS 
- app/cache : fichiers .json en local pour faciliter les tests et les modifications
- Data.ttl : jeu de données original sous la forme de turtle(pretty)
- rapport.pdf : rapport final expliquant le jeu des données et l'application

# Implémentation sous Mac
## Installation de Fuseki
```
brew install fuseki
```
## Lancement du fuseki serveur
```
fuseki-server
```
## Création de la base de données
Génération du propre projet en rendant sur le site web localhost:3030 et en téléchargeant l'ensemble de données à partir du fichier local Data.ttl, puis en souvenant de l'URL **http://localhost:3030/name_project/query** afin de remplacer le point d'arrivée(#endpoint) dans les fichiers .html.

# Lancement de l'application
L'ouverture du fichier index.html vous permettra d'utiliser l'application avec succès. Si la base de données locale n'a pas été installée au préalable, vous pouvez également utiliser le bouton "use cache" pour appeler un fichier local existant afin de générer la visualisation correspondante.

# Utilisation de l'application 
D'une part, vous pouvez tester le fonctionnement actuel du sparql et visualiser les données en cliquant directement sur les boutons existants. D'autre part, vous pouvez également modifier la requête pour l'adapter à d'autres objectifs de votre test. Bien entendu, vous devez veiller à nommer correctement les paramètres entrants.

