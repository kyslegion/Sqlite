<<<<<<< HEAD
# Sqlite
# Installation 
# Créer 
## Base de données
Taper dans l'invite de commande et appuyer sur "Entrée" le texte suivant
```
sqlite3 nomdelabasededonnée.db
```
## Tables
```
CREATE TABLE `auteurs` (
  `ID` INTEGER PRIMARY KEY AUTOINCREMENT,
  `PrenomNom` varchar(255),
  `Photo` varchar(255),
  `Presentation` varchar(10000),
  `Participations` varchar(255),
  `Reseaux` varchar(255),
  `LivresFavoris` varchar(255)
);
```
# Vérifier 
## Base de données
Vérifier l'existence de Base de données avec 
```
.databases
```
## Tables
Vérifier l'existence des tables avec 
```
.tables
```


# Insérer
## Dans les Tables
````

```
=======
# Sqlite
>>>>>>> 5e61fb870bc9fddff7c23f3ec79d4f1bbe8d56a6
