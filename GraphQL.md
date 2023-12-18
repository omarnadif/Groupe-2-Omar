🚨![Logo de GraphQL](https://upload.wikimedia.org/wikipedia/commons/thumb/1/17/GraphQL_Logo.svg/1200px-GraphQL_Logo.svg.png)🚨

GraphQL est un langage de requête pour les API (Interface de Programmation d'Application) et un serveur d'exécution pour exécuter ces requêtes avec les données existantes. Il a été développé par Facebook en 2012 et a été rendu open source en 2015. Depuis lors, il a gagné en popularité et est devenu un standard dans le domaine du développement d'API.

Voici quelques concepts clés associés à GraphQL :

Syntaxe Déclarative : Avec GraphQL, les clients peuvent spécifier exactement les données dont ils ont besoin. Les requêtes sont formulées de manière déclarative, permettant aux développeurs de récupérer précisément les données nécessaires sans surcharger le réseau avec des données inutiles.

Graph Data Model : GraphQL modélise les données sous forme de graphe, où chaque nœud représente un objet et les relations entre les nœuds sont représentées par les arêtes du graphe. Cela permet aux clients de demander des données liées de manière complexe de manière efficace.

Un Seul Point d'Accès : Contrairement aux API REST traditionnelles qui ont souvent plusieurs points d'accès pour différentes ressources, GraphQL expose un seul point d'accès pour toutes les interactions, généralement sous la forme d'un endpoint HTTP unique.

Types et Schéma : GraphQL utilise un schéma pour définir les types de données disponibles et les relations entre eux. Les développeurs peuvent interroger le schéma pour comprendre la structure des données et les opérations possibles.

Résolution des Requêtes : Lorsqu'une requête GraphQL est émise, le serveur GraphQL est responsable de résoudre la requête et de récupérer les données nécessaires à partir des sources de données sous-jacentes (base de données, API externes, etc.). Cela se fait en utilisant des résolveurs, des fonctions qui indiquent comment récupérer chaque champ de la requête.

Mutations : En plus des requêtes pour récupérer des données, GraphQL prend également en charge les mutations pour effectuer des modifications sur les données côté serveur. Les mutations sont similaires aux requêtes, mais elles sont utilisées pour les opérations d'écriture telles que la création, la mise à jour ou la suppression de données.

Abonnements : GraphQL prend également en charge les abonnements, permettant aux clients de recevoir des mises à jour en temps réel lorsqu'une certaine condition est remplie.

En résumé, GraphQL offre une approche flexible et efficace pour la récupération et la manipulation de données sur le web. Sa syntaxe déclarative, son modèle de données basé sur un graphe, et son schéma défini facilitent la création d'APIs puissantes et évolutives. :white_check_mark:


| **Nom**  | GraphQL  |
|---|---|
| **Créé par**  |  Nick Schrock, Dan Schafer, et Lee Byron (Facebook) |
| **Langue**  |  JSON |
| **Description**  |  GraphQL est un langage de requête pour les API  |