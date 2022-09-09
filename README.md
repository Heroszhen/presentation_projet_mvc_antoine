<h1>frameworkphp3wa</h1>
<a href='https://github.com/Heroszhen/frameworkphp3wa' target='_blank'>frameworkphp3wa</a> est un framework que le formateur Cyril nous a appris à créer il y a 2 ans.<br>
Nous pouvons le retrouver dans ce repository: <a href='https://github.com/Heroszhen/frameworkphp3wa' target='_blank'>https://github.com/Heroszhen/frameworkphp3wa</a>
<br>
Voici la structre de ce projet:
<div><img src="images/1.png" alt=""></div>
<br>
<strong>Les détailles:</strong>
<div><img src="images/2.png" alt=""></div>
<div><img src="images/3.png" alt=""></div>
<div><img src="images/4.png" alt=""></div>
<br><br>

Pour lancer le serveur : php -S localhost:8000 -t public
<br><br>

Le framework est construit avec l'achitecture "MVC" : controlleur, vue et modèle.<br>
J'ai également créé des composants et installé des packages pour que le framework fonctionne comme un projet php normal:
<ul>
    <li>Bootstrap 4 : framework css</li>
    <li>FastRoute : système de routage</li>
    <li>FlashBag : composant servant à afficher des messages</li>
    <li>PDO : outil pour la connexion à MySql</li>
    <li>PHPUnit : outil de tests unitaires</li>
    <li>Twig : moteur de template</li>
</ul>
<br>
J'ai aussi importé jquery pour pouvoir utiliser des plugins , par exemple : ckeditor 4.
<br><br>

<h3>Utilisation</h3>
Ajouter une route dans app/Routes.php<br>
Créer un contrôlleur dans src/Controller<br>
Créer un fichier twig dans templates<br>
Si le code est sur sql, la logique est écrite dans un fichier repository dans src/repository
<br><br>
zhen YANG
