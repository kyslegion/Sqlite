Exemple 1
```
INSERT INTO Livres (ID, Nom, NomSansEspaces, Presentation, Description, Couverture, Prix, Genre, Accroche, Lien, Auteur, Edition, Quantite, Annee, NbPages, Ventes, Arriere, Dos)
VALUES (1, 'Titre du livre', 'TitreSansEspaces', 'Présentation du livre', 'Description du livre', 'chemin/vers/couverture.jpg', 19.99, 'Genre du livre', 'Accroche du livre', 'https://lien-du-livre.com', 'Auteur du livre', 'Édition du livre', 10, 2023, 300, 100.0, 'arriere.jpg', 'dos.jpg');
```

Exemple 2
```
INSERT INTO Auteurs (PrenomNom, Photo, Presentation, Participations, Reseaux, LivresFavoris)
VALUES ('John Doe', 'chemin/vers/photo.jpg', 'Présentation de l''auteur', 'Participations de l''auteur', 'Réseaux de l''auteur', 'Livres favoris de l''auteur');

```