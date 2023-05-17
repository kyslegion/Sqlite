
### Lecture complète :
```
SELECT * FROM Livres;
```

### Lecture sélective :
```
SELECT ID, Nom, Prix FROM Livres WHERE Genre = 'Science-fiction';
```

### Lecture triée :
```
SELECT Nom, Prix FROM Livres ORDER BY Prix DESC;
```

### Lecture avec agrégation :
```
SELECT COUNT(*) AS TotalLivres FROM Livres;

```
### Lecture avec filtre :
```
SELECT Nom, Prix FROM Livres WHERE Prix < 20.00;

```

### Lecture avec limitation :
```
SELECT Nom, Prix FROM Livres LIMIT 5;
```
### Lecture avec regroupement et agrégation
```
SELECT Genre, COUNT(*) AS NombreLivres
FROM Livres
GROUP BY Genre;
```

### Lecture avec opérateurs logiques :
```
SELECT Nom, Prix
FROM Livres
WHERE Genre = 'Science-fiction' AND Prix < 20.00;

```
### Lecture avec conditions de date :
```
SELECT Nom, Annee
FROM Livres
WHERE Annee >= 2020;


```