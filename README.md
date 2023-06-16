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

# MySQLQuete3
Tu vas créer des requêtes SQL permettant de modifier des informations dans la table "movie". Tu vas donc : <br><br>
Modifier le nom du film ayant l'ID 5, en le remplaçant par "Men in Black" : <br>
```UPDATE movie SET name='Men In Black' WHERE id='5';``` <br><br>
Modifier le nom et le poster du film ayant l'ID 8, en remplaçant le nom par "Deadpool" et le poster par l'url suivante : "https://upload.wikimedia.org/wikipedia/en/thumb/2/23/Deadpool_%282016_poster%29.png/220px-Deadpool_%282016_poster%29.png" : <br>
```UPDATE movie SET name='Deadpool', poster='https://upload.wikimedia.org/wikipedia/en/thumb/2/23/Deadpool_%282016_poster%29.png/220px-Deadpool_%282016_poster%29.png' WHERE id='8';``` <br><br>
Modifier le commentaire du film ayant l'ID 10, tu vas simplement "supprimer" le commentaire : <br>
```UPDATE movie SET comment = NULL WHERE id = '10';``` <br><br>
