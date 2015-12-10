# Initiation au développement Web (cheat sheet)
Par Brendan Abolivier et Konstantin Sidorenko

## HTML

* `<!DOCTYPE html>` : Doctype (type de document), indique au navigateur le type de contenu qu'on va lui fournir. Se place toujours à la première ligne d'un fichier HTML.
* `<html></html>` : Bloc dans lequel placer tout le contenu HTML.
* `<head></head>` : Contient les informations d'en-tête de la page (titre de la page, méta-données...).
* `<body></body>` : Contient le corps de la page (paragraphes, titres, liens...).
* `<!-- Mon commentaire -->` : Ajoute un commentaire (une annotation) au code source.

### Dans le `<head></head>`
* `<title></title>` : Indique le titre de la page
* `<link rel="stylesheet" href="monstyle.css" />` : Lie la feuille de style *monstyle.css* à la page HTML.
* `<meta name="description" content="Ma description" />` : Ajoute des données (métadonnées) à la page (dans l'exemple ici, donne la valeur "Ma description" à la donnée "description").
* `<meta charset="utf-8" />` : Cas particulier de la balise *meta* définissant le jeu de caractères utilisé.

### Dans le `<body></body>`
* `<section></section>` : Divise une page en plusieurs sections (d'où le nom de la balise).
* `<article></article>` : Divise une section en plusieurs "sous-sections". On peut faire le rapprochement avec un journal, qui contient plusieurs sections (Une, faits divers...), et des articles dans chacune de ces sections.
* `<p></p>` : Définit un paragraphe.
* `<h1></h1>`, `<h2></h2>`, `<h3></h3>`, `<h4></h4>`, `<h5></h5>`, `<h6></h6>` : Définit un titre de niveaux 1 à 6 (les titres étant d'ordre d'importance inversement proportionnel à leur niveau, un titre de niveau 1 étant plus important qu'un titre de niveau 2, et ainsi de suite).
* `<a href="http://www.example.com"></a>` : Définit un lien vers http://www.example.com.

### Attributs génériques
* `href` : Indique la cible d'un lien (généralement utilisé avec les balises `<link />` et `<a></a>`).
* `id` : Identifie un élément dans la page, de façon unique.
* `class` : Identifie un élément dans la page, sans contrainte d'unicité.

## CSS

### Sélecteurs
* `h1` sélectionne toutes les balises `<h1></h1>`.
* `.maclasse` sélectionne toutes les balises ayant l'attribut *class* renseigné avec la valeur *maclasse*.
* `#monid` sélectionne toutes les balises ayant l'attribut *id* renseigné avec la valeur *monid*.
* `section article` sélectionne toutes les balises `<article></article>` se trouvant à l'intérieur d'une balise `<section></section`.
* `section.maclasse` sélectionne toutes les balises `<section></section>` ayant l'attribut *class* renseigné avec la valeur *maclasse*.
* `a[href="http://www.example.com"]` sélectionne toutes les balises `<a></a>` ayant l'attribut *href* renseigné avec la valeur *http://www.example.com*.

### Propriétés
* `color` : Définit la couleur des éléments.
* `background-color` : Définit la couleur d'arrière-plan.
* `background-image` : Définit une image d'arrière-plan.
* `font-size` : Définit la taille du texte.
* `text-align` : Définit l'alignement du texte dans un bloc.
* `font-family` : Définit la police du texte.
* `width` : Définit la largeur d'un élément.
* `height` : Définit la hauteur d'un élément.
* `position` : Définit le mode de positionnement d'un élément.
* `left`, `right`, `bottom`, `top` : Définit le décalage à gauche, droite, en bas, ou en haut (selon le mode de positionnement).
* `border` : Ajoute une bordure à un élément.
* `margin` : Ajoute une marge externe à un élément.
* `padding` : Ajoute une marge interne à un élément.
* `animation` : Permet d'animer un élément.

Couleurs définies dans le langage CSS : `blue`, `grey`, `green`, `white`, `black`, `pink`, `red`, `yellow`, `purple`...

Unités de taille du langage CSS : `pt` (points, notamment utilisés pour les polices d'écriture), `%` (pourcentage de la valeur par défaut), `px` (pixels), `em` (facteur de modification, *1* équivalant à la même valeur que celle par défaut)...

## Ressources pour apprendre

* [MDN (Mozilla Developper Network)](https://developer.mozilla.org/fr/)
* [OpenClassrooms](https://openclassrooms.com/)
* [Codecademy](https://www.codecademy.com/fr)
* [W3Schools](http://www.w3schools.com/) (mais attention aux informations présentes sur ce site)
