# Introduction au MVC

## Petite initiation

- [Comprendre le MVC](MVC.pdf)

EDIT : Bon, en vrai, on va reprendre l'application COGIP et la modifier avec une architecture MVC. Laissez tomber l'interview de webdev pour votre promo. Bisous.

## Projet : Interview d'un webdev

Un site internet avec comme page :
- Making Of : comment vous avez trouvé votre webdev
- présentation de l'entreprise où travaille l'interviewé
- présentation du webdev
- interview (voir liste de questions)
- Conclusion (analyse/impression personnelle)

Il faut un MVC :
- un dossier **controller** avec le routeur, celui qui va rediriger
- un dossier **model** où on va mettre le traitement PHP (tu sais, tout ce qui se trouve au-dessus du doctype)
- un dossier **view** avec toutes les pages visuelles
- un fichier **config.php** avec les infos de connexion (user, password, login, host)
- un fichier **connexion.php** avec la connexion à la DB
- un fichier **index.php** qui inclut le connexion.php et le config.php, et également le contrôleur.

La liste des questions est [disponible ici](interviewwebdev.md).
