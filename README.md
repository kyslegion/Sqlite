
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
INSERT INTO livres (ID, Nom, NomSansEspaces, Presentation, Description, Couverture, Prix, Genre, Accroche, Lien, Auteur, Edition, Quantite, Annee, NbPages, Ventes, Arriere, Dos)
VALUES (1, 'Titre du livre', 'TitreSansEspaces', 'Présentation du livre', 'Description du livre', 'chemin/vers/couverture.jpg', 19.99, 'Genre du livre', 'Accroche du livre', 'https://lien-du-livre.com', 'Auteur du livre', 'Édition du livre', 10, 2023, 300, 100.0, 'arriere.jpg', 'dos.jpg');

```
=======
# Sqlite

