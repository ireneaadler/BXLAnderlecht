# Travail Intégration

Ce que nous appelons un travail d'intégration, c'est un travail avec des consignes à respecter impérativement. Les TI conclut une période d'apprentissage et vous permette de mettre en pratique ce que vous avez appris. Ils permettent également à vos formateurs de vous évaluer, savoir où vous avez encore des difficultés et savoir quels sont vos acquis. Enfin, ces travaux, s'ils sont réalisés correctement, peuvent faire partie d'un portfolio que vous pourriez montrer à un employeur.

**!!! N'oubliez pas de nommer votre repo "TI-FrontEnd-AllezCine" !!!**

**Un repo par projet ! Et n'oubliez pas votre readme.md !!!**

## Travail d'intégration Front-End

Ce TI conclut les deux mois de front-end que nous avons eus ensemble.
Vous avez **3 travails en rendre**.
- Un site en ONE PAGE avec un design fournit ([yes !](layout-one-page.jpg).
- Un site de fans (Design non fourni)
- Création d’une newsletter pour faire la promo des nouveautés sur votre site.

Pour cela, vous devez utiliser toutes les techno vues depuis le début, c’est à dire :
- HTML
- CSS
- JavaScript
- jQuery
- Responsive design
- Bootstrap
- Font Awesome Icons
et autres

Remarque : Le style par défaut de Bootstrap soit complètement absent (utilisez Bootstrap sans que l’on puisse voir que Bootstrap a été utilisé).

### A . Site avec LAYOUT

Vous allez réaliser, en groupe, un site internet de location et vente des films. ATTENTION, il s'agit d'un site en one-page !

[Cliquez ici pour voir le layout](layout-one-page.jpg)

#### Entrer sur le site
Lorsqu’on entre sur le site il faut contraindre l’utilisateur à entrer son âge.
S’il a 18 ans et plus, l’autoriser à entrer sur le site, sinon le rediriger sur le site de moins de 18 ans. (Pour cela utiliser JS ou Jquery pour un pop-up).

Une fois sur le site, faire apparaître n’importe où sur le site une box pour la mise en garde de COOKIES.(on en voit ces derniers temps partout sur le net)

 Lorsqu’on clique sur le bouton LOGIN faire apparaître en JS ou Jquery dans une box un formulaire de connexion.
 Ce formulaire de connexion contiendra :
 - identifiant,
 - password,
 - un bouton OK,
 - un lien “ S’enregistrer”,
 - un lien “Si vous avez oublié votre mot de passe”
 - et un lien CANCEL.

(Difficulté, faire disparaître le formulaire lorsqu'on clique sur CANCEL ou sur le formulaire).

#### Menu
Un **menu** en bootstrap avec des sous-menus. (**Menu oignon pour le responsive**).

Comme c’est une onepage, les liens du menu doivent pointer vers les sections dédiées.

### En-tête
Le **jumbotron** de l'entête doit faire 100% de la largeur de l'écran dans lequel il y a un slide (Cf layout). Faire fonctionner le **slide** en CSS ou en JS ou Jquery)

### Les boutons réseaux sociaux
Les **boutons de réseaux sociaux** sont en position fixe. Si on clique sur un bouton, il doit s’allonger avec une animation (ici utilisez juste du CSS).

#### Section Films
Chaque film doit comporter :
- une affiche,
- un titre,
- l’année de sortie,
- et le genre.

Si on clique sur l’image ou titre du film, faire apparaître dans un modal (Bootstrap) le trailer youtube du film, la description, le réalisateur, l’année de sortie du film, le genre, les acteurs…

#### Section Featured Movies
Créer des boutons pour filtrer les films par genre (Jquery ou JS).
Si on clique sur le bouton ACTION par exemple, afficher uniquement les films d’actions, etc...

Lorsqu’on clique sur le bouton “plus des films”, afficher les autres films cachés. Faire disparaître le bouton “plus des films” et le remplacer par le bouton “Moins des films” si on clique sur “moins des films”, cacher les films et faire réapparaître le bouton “plus des films“  (En jQuery sera plus facile, avec un toggle par exemple).

#### Section Shop Movie
Utiliser les deux petits boutons à droite pour faire défiler les films de gauche à droite et vise-versa (Jquery, bootstrap, JS au choix)

#### Section Contact Us
Créer un formulaire et afficher dans un 
les entrées du formulaire lorsqu’on clique sur “Send Message”. (Pas de traitement en php, prochainement promis)

Bonus: mettre une map dans la section Contact us.


#### Section Footer
Faites en sorte que lorsqu’on clique sur le petit bouton orange avec la flèche blanche, on monte jusqu’à l'entête du site, le petit bouton disparaît une fois que l'entête apparaît.

CONTRAINTE : créer ce bouton en pur JS avec createElement(), createTextNode() et compagnie(), l’afficher sur le DOM, le positionner puis le styler en CSS dans la feuille de style.

FAITES QUE LE SITE SOIT RESPONSIVE (Bootstrap + Media queries)

Si quelque chose a été oublié, contactez Eric pour qu'il l'ajoute à la liste que vous avez déjà à faire. //edit Eric : hihihihihi Je suis diabolique.


### B. Site de fans
Il n'y a pas de layout imposé mais rien ne vous empêche de reprendre celui de l'exercice A.

Réaliser un site internet sur un personnage de ton choix (série télé, film, jeu vidéo,...). Le mieux étant que ce personnage soit cross-media (par exemple Batman est présent dans des films, dans des séries, des jeux vidéos, des comics,...) pour la partie "présentation". Tâchez de choisir un personnage qui soit dans au moins deux media.

Minimum 5 pages avec :
- **Présentation**
- **Biographie**
- **Photographies** (Galerie de photos du personnages),
- **Goodies** (page de simulation d'achat de produits dérivés),
- **Contact** (je vous fais pas un dessin)

**BONUS PAS OBLIGATOIRE** : Au lieu de faire 5 pages, faites 5 onglets et réalisez ce site sur une seule page web.


#### Conditions imposées

**Présentation** : la particularité de cette page est qu'elle contiendra un sous-menu avec des onglets. Un onglet par medium dans lequel le personnage apparaît. (minimum deux onglets). Pour reprendre l'exemple de Batman, vous pourriez faire un onglet [Batman 1989] et parler brièvement de Batman dans ce film puis un autre onglet [Gotham] et parler brièvement de Batman dans cette série. Si vous n'êtes pas inspiré pour le contenu, vous pouvez reprendre du texte du wikipedia mais MENTIONNEZ VOS SOURCES ! (au moins dans le readme.md qui se trouvera obviously dans le repo de votre projet).

**Biographie** : il faudra que la vie du personnage soit “chapitrée” (exemple : "enfance, adolescence, vie d'adulte, fin de vie". OU encore "saison 1, saison 2, ..."). On devra cliquer sur le titre du chapitre pour dérouler le texte. Cela permettra d'éviter les spoilers. (par exemple avec une méthode toggle avec peut-être un paramètre de vitesse ?)

**Photographies** : réalisez une galerie de photos du personnage. Utilisez du jQuery pour rendre ça joli. Un caroussel, une lighbox,... Faites le code vous-même ou utilisez un plugin, faites comme vous voulez.

**Goodies** : Une page avec une liste de produits dérivés avec le montant par pièce, un champs pour que l'utilisateur indique combien d'items il veut acheter. En cliquant sur le bouton [Prévisualisation avant achat], l'utilisateur voit le total de son achat. L'affichage se fait soit dans un pop-up (alert) ou dans la page HTML (prévoyez un emplacement pour l'affichage).
BONUS : Si le montant est inférieur à 15€, l'utilisateur devra payer 10€ de frais de livraison. Si le montant est compris entre 16€ et 30€, les frais s'élèvent uniquement à 7€. Si le montant de la commande s'élève à plus de 31€, les frais de livraison sont gratuits.

**Contact** : réalisez un formulaire de contact qui vérifiera que tous les champs sont remplis. Si les champs sont vides, attribuez-leur un fond de couleur pour les mettre en évidence et indiquez en dessous des champs vides une mention "ce champs doit être renseigné".

#### Conseils

1. Réalisez d'abord le HTML, placez-y le contenu, ensuite écrivez les scripts nécessaires.
2. D'ailleurs, n'oubliez pas de bien :
- coder correctement votre HTML (les titres avec des h1, h2 ; les paragraphes dans des balises p ; ...). Un code bien organisé et toujours plus facile à traiter.
- nommer correctement vos ID. Utilisez des noms qui aient du sens, facile à vous situer sur votre page.

### C. La newsletter (BONUS)

Utiliser ce site https://putsmail.com/tests/new  pour tester votre newsletter.
Vous pouvez utiliser les TABLES, ou du HTML5 ( certains webmails acceptent du HTML5 mais mais mais attention avec du CSS)

Référence: http://pictures.yvesrocher.com/NL/2017-06/06/be-fr/jun_6_be-fr_a2_online.html
Voici une newsletter que j’ai reçu de la part de Yves Rocher, s’inspirer à souhait et c’est essentiellement des tables.

Bonne chance et bon courage. (PS : on vous aime)

## REMARQUES :
Vous travaillez en groupe. Organisez-vous. Communiquez (rappelez-vous les bienfaits des réunions scrum). Vous avez jusque vendredi midi pour terminer ce site.

Si vous avez des remarques ou des questions, n'hésitez pas à utiliser l'onglet [Issues](https://github.com/becodeorg/BXLAnderlecht/issues) de GitHub pour vous exprimer.
