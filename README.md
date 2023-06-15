# MySQLQuete2
Tu vas créer des requêtes SQL permettant d'ajouter du contenu dans la table "movie". Tu vas donc : <br><br>
Ajouter un film sans spécifier les noms des colonnes dans la requête : <br>
```INSERT INTO movie VALUES (null, 'The Flash', 'https://fr.web.img6.acsta.net/pictures/23/04/26/10/33/4339332.jpg', 'nul selon Angélina');``` <br><br>
Ajouter un film en spécifiant toutes les colonnes sauf l'ID : <br>
```INSERT INTO movie (name, poster, comment) VALUES ('The Flash', 'https://...', 'nul selon Angélina');``` <br><br>
Ajouter 3 films dans une même requête en spécifiant toutes les colonnes sauf l'ID : <br>
```INSERT INTO movie (name, poster, comment) VALUES ('Licornes contre les vampires', 'https://...', 'ça vaut le coup doeil'), ('Les licornes à saint Tropez', 'https://...', 'ça me rappelle un vieux film avec des gendarmes'), ('La revanche des licornes', 'https://...', 'mieux que le premier volume');``` <br><br>
Ajouter un film en spécifiant uniquement son nom : <br>
```INSERT INTO movie (name) VALUES ('La licorne is back');``` <br>
