Exemple1
````
CREATE TABLE Livres (
  ID INT NOT NULL PRIMARY KEY,
  Nom VARCHAR(255),
  NomSansEspaces VARCHAR(255) NOT NULL,
  Presentation VARCHAR(10000) NOT NULL,
  Description VARCHAR(255),
  Couverture VARCHAR(255),
  Prix FLOAT,
  Genre VARCHAR(255),
  Accroche VARCHAR(255),
  Lien VARCHAR(255),
  Auteur VARCHAR(255),
  Edition VARCHAR(255),
  Quantite INT,
  Annee INT NOT NULL,
  NbPages INT NOT NULL,
  Ventes FLOAT NOT NULL,
  Arriere VARCHAR(255) NOT NULL,
  Dos VARCHAR(255) NOT NULL
);

```
Exemple2
```
CREATE TABLE `Auteurs` (
  `ID` INTEGER PRIMARY KEY AUTOINCREMENT,
  `PrenomNom` varchar(255),
  `Photo` varchar(255),
  `Presentation` varchar(10000),
  `Participations` varchar(255),
  `Reseaux` varchar(255),
  `LivresFavoris` varchar(255)
);
```