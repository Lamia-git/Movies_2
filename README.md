### Projet Movies 2

Présentation Méthodologie:
CLIENT : Christophe Chevalier Service : FLOUPICS Domaine Service : VOD Résalisé Par : TEAM B PRODUCTIONS ( Lamia, Alicia, Matthias, Mayel)

#### I) Rappel problématique et besoin du client:

Toujours dans l'idée de se lancer dans le domaine de la VOD. Vous nous sollicitez cette fois pour adapter le travail mis en place avec SQlite3 sous le format PostgreSQL. Avec une demande sur l'amélioration des données. 

**PostgreSQL** est un système de gestion de base de données relationnelle et objet. C'est un outil libre disponible selon les termes d'une licence de type BSD.

**pgAdmin** est gestionnaire de bases de données Open Source pour l'administration des bases PostgreSQL. Il comprend une interface graphique administrateur, et permet d'écrire des requêtes SQL simples comme complexes. Un éditeur de code procédural est également intégré.


#### 2) Prérequis:

- Python 3.8.6  (requirement.txt)
- PostgresSQL 13
- Pgadmin 4

#### 3) Rendu Final et documents:

Les documents seront disponibles sur Github à cette adresse

lien Github: https://github.com/Lamia-git/Movies_2

Nous disposons toujours des tables en format csv dans notre dossier « movies csv » :

-movies.csv

-links.csv

-tags.csv

-links.csv

Le script final pourra être visualisé sur le document Jupyter notebook "Scripts_movie_2.ipynb "

#### 4) Étapes Clés du projet 

Le script_movie_2.ipynb nous permet par plusieurs étapes d'insérer nos tables en format csv sous format PostgreSQL et leur exploitation sur Pgadmin4. 

Dans un premier temps nous établissons une **connexion** avec une base PostgreSQL et nous **créons une data base** "movie2" sur PgAdmin4. 

Puis, nous **créons notre table** "movie" par requête SQL en précisant nos colonnes movieID, title, genres et en rajoutant une colonne année après **retraitement** de notre table. En effet, dans la table movie.csv de départ deux informations sont contenues dans la colonne "title" le titre et l'année. Ce retraitement va permettre de mettre en évidence d'autres tendance ou faire des classements des films par leur date. 
Après la création, il faut faire **l'insertion** puis la **lecture** des données. 

Enfin, nous pouvons **visualiser** l'insertion réussis sur pgAdmin4 des tables. 


Un autre traitement des tables ratings et tags auraient pu être fait avec la valeur timestamp. Et deux colonnes date et heure auraient pu être alors rajoutés à nos tables. 

Lien Utile pour réalisation du projet :
   
 Télécharger PostgreSQL 13 et PgAdmin4 
 
 https://www.postgresql.org/download/ 
 
 https://www.pgadmin.org/download/
    

Vous souhaitant bonne réception.
