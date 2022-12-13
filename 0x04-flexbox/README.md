# 0x04-flexbox

## Exercice 0 :
On demande de copier le contenu des fichiers HTML et CSS de départ de cette tâche dans les fichiers qui doivent être produits et de faire les changements nécessaires selon la description de la tâche.

Lorsqu'on utilise display: flex; sur un conteneur, tous les éléments enfants directs deviennent des éléments flex (et ne sont plus des éléments en ligne ou en bloc).

Avec display: flex, les marges ne s'effondrent pas comme elles le feraient avec des éléments en bloc. Rappelez-vous également que flexbox est un système en un seul dimension (contrairement à CSS Grid qui est un système à deux dimensions).

Dans la section /* Grid de votre CSS :

    Ajoutez un sélecteur pour la classe row
        Propriété : display, Valeur : flex
        => Maintenant, tous les enfants de la classe row sont des éléments flex

    Supprimez complètement la déclaration row::after

    Supprimez float: left à l'intérieur de [class*='col-']
    => Tous les éléments devraient apparaître de la même manière qu'avant en utilisant le flottement.
## Exercice 1:
Pour cette tâche, utilisez les fichiers de la tâche précédente comme base:

    Dans la balise de section la plus externe pour les services, ajoutez la classe "section-services".
    Dans la balise de section la plus externe pour les travaux, ajoutez la classe "section-works".
    Dans la balise de section la plus externe pour "à propos", ajoutez la classe "section-about-us".
    Dans la balise de section la plus externe pour les dernières nouvelles, ajoutez la classe "section-latest-news".
    Dans la balise de section la plus externe pour les témoignages, ajoutez la classe "section-testimonial".
    Dans la balise de section la plus externe pour les contacts, ajoutez la classe "section-contact".
## Exercice 2:
Pour cette tâche, utilisez les fichiers de la tâche précédente:

La propriété flex-direction indique comment les éléments flex sont placés sur l'axe principal et leur direction (normale ou inversée).

flex-direction est parfois utilisé lors de la conception de sites Web adaptatifs. Certains éléments peuvent être mieux lorsqu'ils sont en mode colonne sur les appareils mobiles et en mode ligne sur les ordinateurs de bureau.

row-reverse et column-reverse devraient être utilisés dans des situations spécifiques. L'ordre visuel des éléments devrait être le même visuellement et dans le code HTML. Reportez-vous à flex-direction - CSS: Cascading Style Sheets | MDN pour plus d'informations.

Dans votre fichier CSS:

    Avant /*** 4. CARD **/, ajoutez un nouveau commentaire: / Section Latest news ============================= */
    Sous cette section de commentaire, ciblez la classe row à l'intérieur de la classe section-latest-news
        Propriété: flex-direction, Valeur: row-reverse

Les dernières nouvelles devraient apparaître dans un ordre inversé.

## Exercice 3:
Pour cette tâche, utilisez les fichiers de la tâche précédente:

flex-wrap est une propriété qui peut forcer les éléments flex à être sur une ou plusieurs lignes. Apprenez-en plus ici.

Dans la section Services de 3-index.html, supprimez la deuxième ul et placez les 3 lielements sous la première ul.

Maintenant, dans votre fichier CSS, avant /*** 4. CARD **/, ajoutez un nouveau commentaire: / Section SERVICES ============================= */

Sous cette section de commentaire, ajoutez un nouveau sélecteur ciblant la classe row à l'intérieur de la classe section-services.

    Propriété: flex-wrap, Valeur: wrap

Repo:

    Dépôt GitHub: holbertonschool-web_front_end
    Répertoire: 0x04-flexbox
    Fichier: 3-index.html, 3-styles.css
## Exercice 4:
Pour cette tâche, utilisez les fichiers de la tâche précédente:

Dans le fichier 4-styles.css, dans la section Grid:

    Dans le sélecteur .col-1-3, remplacez la largeur actuelle par calc((100% / 3) - 2rem).
    Dans le sélecteur .col-1-2, remplacez la largeur actuelle par calc((100% / 2) - 2rem).
    Dans [class*='col-'], supprimez la déclaration padding et définissez la propriété margin sur 1rem.
    Dans la déclaration ul.row, remplacez le margin actuel par -1rem.

Repo:

    Dépôt GitHub: holbertonschool-web_front_end
    Répertoire: 0x04-flexbox
    Fichier: 4-index.html, 4-styles.css

## Exercice 5:
Pour cette tâche, utilisez les fichiers de la tâche précédente:

Dans votre fichier 5-index.html, à l'intérieur de la section Header:

    Enveloppez le div avec la classe header-logo et le nav avec la classe navbar-menu avec un div qui a header-container comme classe.

Dans votre fichier 5-styles.css:

    Dans la section /* Header, ajoutez un sélecteur pour la classe header-container.
        Propriété: display, Valeur: flex
        Propriété: justify-content, Valeur: space-between
    Supprimez les règles header-logo et header-logo a.
    Supprimez la règle navbar-menu.
    Dans la section variables, supprimez les variables suivantes:
        header-logo-position
        header-logo-link-display
        header-logo-link-position
        header-logo-link-top
        header-logo-link-left.

Repo:

    Dépôt GitHub: holbertonschool-web_front_end
    Répertoire: 0x04-flexbox
    Fichier: 5-index.html, 5-styles.css
## Exercice 6:
Dans 6-styles.css, à l'intérieur de la section /* Navbar:

    Dans le sélecteur de classe nav, définissez la propriété display sur flex.
    À l'intérieur du sélecteur .nav .nav-item, supprimez la déclaration display.
    Ciblez .nav-item + .nav-item à l'intérieur de la classe nav et déplacez la déclaration de marge de .nav .nav-item dans ce nouveau sélecteur.
    Dans la section variables, modifiez la valeur de la variable nav-item-margin pour qu'elle soit 0 0 0 2rem.

Repo:

    Dépôt GitHub: holbertonschool-web_front_end
    Répertoire: 0x04-flexbox
    Fichier: 6-index.html, 6-styles.css
## Exercice 7:
Dans 7-styles.css, dans la section /* Header, dans le sélecteur de classe header-container, définissez la propriété align-items sur center.

Repo:

    Dépôt GitHub: holbertonschool-web_front_end
    Répertoire: 0x04-flexbox
    Fichier: 7-index.html, 7-styles.css
## Exercice 8:
Dans 8-styles.css, dans la section /* Section HERO:

    Dans le sélecteur ciblant la classe section-inner dans la classe section-hero, supprimez le padding et remplacez-le par les propriétés suivantes:
        display: flex
        flex-direction: column
        align-items: flex-start
        justify-content: center
        min-height: 50vh

Repo:

    Dépôt GitHub: holbertonschool-web_front_end
    Répertoire: 0x04-flexbox
    Fichier: 8-index.html, 8-styles.css
## Exercice 9:
Dans 9-styles.css, après la section /* Section SERVICES, créez une section /* Section ABOUT US. À l'intérieur de cette nouvelle section, ciblez toutes les classes qui commencent par col- à l'intérieur de la classe section-about-us et définissez la propriété align-self sur center.

Repo:

    Dépôt GitHub: holbertonschool-web_front_end
    Répertoire: 0x04-flexbox
    Fichier: 9-index.html, 9-styles.css
## Exercice 10:
Dans 10-styles.css, à l'intérieur de la section /* Section HERO:

    Après .section-hero, ajoutez un nouveau sélecteur de classe hero-homepage (vous devrez ajouter cette classe plus tard dans vos fichiers html).
    Déplacez toutes les déclarations à l'intérieur de section-hero dans le nouveau sélecteur de classe hero-homepage.
    Dans le sélecteur de classe section-hero, définissez les propriétés suivantes:
        position: relative
        margin-top: -8.5rem
    Ciblez ensuite .section-body à l'intérieur de la classe section-hero et définissez la propriété padding sur 10rem 4rem.
    Ciblez ensuite .section-category à l'intérieur de la classe section-hero et définissez les propriétés suivantes:
        color: point to the variable color-white
        text-transform: uppercase

Repo:

    Dépôt GitHub: holbertonschool-web_front_end
    Répertoire: 0x04-flexbox
    Fichier: 10-article.html, 10-styles.css
## Exercice 11:
Dans 11-article.html, dans la section Hero:

    Ajoutez la classe hero-article sur la balise <header> qui se trouve dans <main>.
    Ajoutez cette image de fond (pic-article-02.jpg) en tant qu'inline style toujours sur la balise <header>.
    À l'intérieur de la section avec la classe section-inner, ajoutez une balise span avec la classe section-category et le texte Digital Life.
    En dessous, ajoutez une balise h1 avec la classe section-title et le texte suivant: Ut alios omittam, hunc appello, quem ille unum secutus est.

À la fin de 11-styles.css, créez une nouvelle section de commentaire:

/*** ARTICLE PAGE **/
/ Section HERO (article)
============================= */

Ciblez la classe hero-article et définissez les propriétés suivantes:

    background-size: 150rem 100rem
    background-position: 50% 0

Ciblez l'élément pseudo before de la classe hero-article et définissez les propriétés suivantes:

    content: empty
    background: rgba(0, 0, 0, 0.8)
    position: absolute
    top: 0
    right: 0
    left: 0
    bottom: 0
    z-index: 0

Ciblez la classe section-inner à l'intérieur de la classe hero-article et définissez les propriétés suivantes:

    text-align: center
    align-items: center
    min-height: 40vh

Ciblez la classe section-body à l'intérieur de la classe hero-article et définissez les propriétés suivantes:

    position: relative
    padding: 7rem 0 0
    z-index: 2

Repo:

    Dépôt GitHub: holbertonschool-web_front_end
    Répertoire: 0x04-flexbox
    Fichier: 11-article.html, 11-styles.css
## Exercice 12:
Dans votre fichier 12-article.html, dans la section Hero:

    Après l'en-tête, créez un div et définissez sa classe sur main-article (ce div sera en frères avec l'en-tête de la section Hero)
    Créez un div à l'intérieur du div main-article et définissez sa classe sur container
    Créez un div avec la classe post à l'intérieur du div container
    À l'intérieur du div post:
        Créez un nouvel article avec la classe post-content
        Sous l'article post-content, ajoutez le commentaire <!-- Aside section -->
        Frère de l'article post-content et après le commentaire, créez un aside avec la classe post-aside
        À l'intérieur de aside post-aside, créez 2 divs:
            Le premier avec la classe post-meta
            Le second avec la classe post-share

Dans votre fichier 12-styles.css:

    Ciblez la classe main-article
        Propriété : padding, Valeur : 5rem 0
    Ajoutez le commentaire séparateur ci-dessous

/* Post
============================= */

    Ciblez la classe post
        Propriété : display, Valeur : flex
    Ciblez la classe post-content
        Propriété : width, Valeur : 100%
    Ciblez la classe post-aside
        Propriété : order, Valeur : -1
        Propriété : min-width, Valeur : 20%

Référentiel:

    Référentiel GitHub : holbertonschool-web_front_end
    Répertoire : 0x04-flexbox
    Fichier : 12-article.html, 12-styles.css
## Exercice 13:
