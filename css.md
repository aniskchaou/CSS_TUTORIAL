
## Le CSS, ou Cascading StyleSheets

**CSS est le diminutif de Cascading StyleSheets**, ou feuilles de styles en cascade.

Le CSS a été créé en 1996 et a pour rôle de mettre en forme du contenu en lui appliquant ce qu’on appelle des styles.
le CSS (ou feuille de style), c'est un petit fichier (exemple "style.css") dans lequel vous allez définir l'ensemble des choix de couleurs, type de police (arial, comic sans MS, etc), taille du texte...

  

## **La syntaxe du CSS et notion d'héritage**

 
La syntaxe CSS est simple, elle se compose d'un selecteur et une propriété associé à une valeur :  
  
**Structure syntaxique : selecteur { propriété : valeur }  
Un exemple concret : body { background: #eeeeee; }  
**

**Combination de selecteurs**  
Vous pouvez aussi combinez les éléments HTML qui regroupent les memes caractéristiques :  
**h1, h2, h3, h4, h5, h6 { color: #009900; font-family: Georgia, sans-serif;}**  

## **Mettre des commentaires dans le CSS**

Vous pouvez mettre des commentaires dans votre code avec la syntaxe suivante :  
/* Commentaire ici */  


## **utiliser css**

Votre code CSS peut être placé à 3 endroits dans le site différentes dans la page.  
  
  
1 Internal: Dans la page HTML  
2 External: Dans un fichier indépendant  
3 Dans l'élément HTML lui-même  
  
  

## **Dans le code HTML de la page**

 
Premier choix: mettre le code CSS dans la page HTML, entre les deux balises < header> et < /header>.  

***< head>< title>titre de ma page < style type="text/css"> Ici le code CSS < /style>*** 
  

## **Dans un fichier indépendant**

 
Deuxième choix : dans un fichier indépendant appelé en général style.css  
Le fichier CSS doit aussi être inclut entre les deux balises HTML : < header>.  
  
**< head>  
< title>titre de ma page  < /title>
< link rel="stylesheet" type="text/css" href="style.css"/>**  
  
  

## **Dans la balise HTML**

Enfin,il possible de mettre un style directement dans une balise HTML : 
**< body style="margin:0px;"> Syntaxe du CSS et notion d'héritage**  
  

## **Les classes**

Il est possible de changer une parti au sein de ce paragraphe, comme mettre une phrase en vert et gras sans toucher au reste.  
  
**Coté HTML : Le code HTML me donnera :**  

< p>Voici un texte **< span class="greenboldtext">** avec une phrase en gras et vert  alors que le reste ne change pas **< /span>** < /p>
  
**Coté CSS : Dans ma feuille de style:**  
.greenboldtext{  
font-size: small;  
color: #008080;  
font-weight: bold;  
}  
  

## **ID**

La déclaration d'un ID en CSS est identique à la notion de class à une execption près :  
On ne peut déclarer une seule fois un ID  
  
**cote HTML**  
**< div id="container">** Ici le code HTML relatif au contenu..  **< /div>**
  
**cote CSS**  
#container{  
width: 80%;  
padding: 20px;  
border: 1px solid #666;  
background: #ffffff;  
}  
  
Remarque : On utilise un  # pour les  id  et un "." pour les  classes.

## Background (arrière-plan)

Cette liste de propriétés permet de définir la couleur ou l'image qui sera utilisée en fond de page ou en arrière plan d'élément. Le site MammouthLand propose une page détaillée sur l'utilisation de ces propriétés.

**background**	Ensemble de propriétés de l'arrière-plan.
*body {background: url(watermark.jpg) repeat fixed}*
background:  #ffffff url("img_tree.png") no-repeat right top;
**background-attachment**	Mode de défilement de l'image d'arrière-plan.
**background-color**	Couleur de l'arrière-plan.
*.highlighter {background-color: yellow}*
**background-image**	Image d'arrière-plan.
**background-position-x**	Position horizontale de l'image d'arrière-plan.
**background-position-y**	Position verticale de l'image d'arrière-plan.
**background-position**	Position de l'image d'arrière-plan.
background-position:  right top;
**background-repeat**	Mode de répétition de l'image d'arrière-plan.
body{ background-repeat:  repeat-x; }
**layer-background-image**	Image d'arrière plan et de la bordure dans Netscape Navigator.
**layer-background-color**	Couleur d'arrière plan et de la bordure dans Netscape Navigator.

## Border (bordure)

Cette liste de propriétés permet de définir les caractéristiques des bordures de l'élément. Pour la façon particulière dont Internet Explorer interprête parfois ces propriétés, reportez-vous à la propriété border.

Voir également la famille "outline" qui permet de jouer sur l'encadrement du contenu d'un élément.

**border**	Caractéristiques des bordures.
p {border: 10px groove darkred}
**border-bottom**	Caractéristiques de la bordure du bas.
**border-bottom-color**	Couleur de la bordure du bas.
**border-bottom-style**	Style de la bordure du bas.
**border-bottom-width**	Epaisseur de la bordure du bas.
**border-collapse**	Mode d'encadrement des cellules adjacentes.
**border-color**	Couleur des bordures.
**border-left**	Caractéristiques de la bordure de gauche.
border-left:  6px solid red;
**border-left-color**	Couleur de la bordure de gauche.
**border-left-style**	Style de la bordure de gauche.
**border-left-width**	Epaisseur de la bordure de gauche.
**border-right**	Caractéristiques de la bordure de droite.
**border-right-color**	Couleur de la bordure de droite.
**border-right-style**	Style de la bordure de droite.
**border-right-width**	Epaisseur de la bordure de droite.
**border-spacing**	Espacement entre deux traits de cellules adjacentes.
**border-style**	Style des bordures.
border-style:  solid
**border-top**	Caractéristiques de la bordure du haut.
**border-top-color**	Couleur de la bordure du haut.
**border-top-style**	Style de la bordure du haut.
**border-top-width**	Epaisseur de la bordure du haut.
**border-width**	Epaisseur des bordures.
**-moz-border-radius**	Permet de définir un coin arrondi des bordures (pour Mozilla seulement)
**-moz-border-radius-bottomleft**	Permet de définir un coin arrondi pour une bordure (pour Mozilla seulement)
**-moz-border-radius-bottomright**	Permet de définir un coin arrondi pour une bordure (pour Mozilla seulement)
**-moz-border-radius-topleft**	Permet de définir un coin arrondi pour une bordure (pour Mozilla seulement)
**-moz-border-radius-topright** Permet de définir un coin arrondi pour une bordure (pour Mozilla seulement)

## Couleur

Cette famille regroupe toutes les propriétés consacrées à la couleur.

Les normes HTML et CSS permettent de définir les couleurs de 3 façons différentes. Pour en savoir plus, consultez notre page consacrée à la couleur.

**background-color**	Couleur de l'arrière-plan.
**border-bottom-color**	Couleur de la bordure du bas.
**border-color**	Couleur des bordures.
**border-left-color**	Couleur de la bordure de gauche.
**border-right-color**	Couleur de la bordure de droite.
**border-top-color**	Couleur de la bordure de droite.
**color**	Couleur de l'avant plan (texte, par exemple).
**layer-background-color**	Couleur d'arrière plan et de la bordure dans Netscape.
**outline-color**	Couleur de l'encadrement de l'élément.
**scrollbar-3dlight-color**	Aspect de l'ascenseur (Explorer seulement).
**scrollbar-arrow-color**	Aspect de l'ascenseur (Explorer seulement).
**scrollbar-base-color**	Aspect de l'ascenseur (Explorer seulement).
**scrollbar-darkShadow-color**	Aspect de l'ascenseur (Explorer seulement).
**scrollbar-face-color**	Aspect de l'ascenseur (Explorer seulement).
**scrollbar-highlight-color**	Aspect de l'ascenseur (Explorer seulement).
**scrollbar-shadow-color**	Aspect de l'ascenseur (Explorer seulement).
**scrollbar-track-color**	Aspect de l'ascenseur (Explorer seulement).

## Divers

**cursor**	Forme du curseur pour la souris.
**filter (new style)**	Filtre graphique.
**filter (old style)**	Filtre graphique.
**!important**	Donne la priorité à une définition CSS.
**-moz-opacity**	Transparence/opacité de l'élément (pour Mozilla seulement)
**opacity**	Transparence/opacité de l'élément.
**scrollbar-3dlight-color**	Aspect de l'ascenseur (Explorer seulement).
**scrollbar-arrow-color**	Aspect de l'ascenseur (Explorer seulement).
**scrollbar-base-color**	Aspect de l'ascenseur (Explorer seulement).
**scrollbar-darkShadow-color**	Aspect de l'ascenseur (Explorer seulement).
**scrollbar-face-color**	Aspect de l'ascenseur (Explorer seulement).
**scrollbar-highlight-color**	Aspect de l'ascenseur (Explorer seulement).
**scrollbar-shadow-color**	Aspect de l'ascenseur (Explorer seulement).
**scrollbar-track-color**	Aspect de l'ascenseur (Explorer seulement).
**visibility**	Détermine si l'élément est affiché sur la page.
**white-space**	Gestion des espaces multiples et des retours chariot.

## Liste

Ces propriétés premettent de définir la façon d'afficher les éléments de type < LI>, < UL> et < OL> ainsi que les éléments < DT> et < DD> (listes de définitions)

**list-style-image**	Image remplaçant les puces dans les listes.
**list-style-position**	Détermine si la puce doit être affichée à l'intérieur ou à l'extérieur (en retrait négatif) du bloc de contenu de liste.
**list-style-type**	Définit le type de puce à afficher pour une liste.
**list-style**	Ensemble de caractéristiques pour une liste.
**marker-offset**	Position de la puce ou du numéro dans une liste.

## Outline (encadrement)

Alors que les propriétés "border" permettent d'attribuer une bordure aux éléments, les propriétés "outline" attribuent un cadre au contenu des éléments.

**outline-color**	Couleur de l'encadrement de l'élément.
**outline-style**	Couleur d'encadrement de l'élément.
**outline-width**	Epaisseur de l'encadrement de l'élément.
**outline**	Encadrement de l'élément.

## Position et dimensions

Ces propriétés permettent de gérer la mise en page de votre site.

**bottom**	Position basse d'un élément.
**clear**	Gestion de l'habillage (en relation avec la propriété "float")
**clip**	Définit la partie visible de l'élément.
**display**	Façon d'afficher un élément.
display:  inline;
**float**	Positionnement flottant (relatif) d'un élément par rapport à un autre.
float:  right;
**height**	Définit la hauteur d'un élément
**left**	Position gauche d'un élément
**margin**	Marges extérieures de l'élément.
**margin: 25px 50px 75px 100px;**

-   top margin is 25px
-   right margin is 50px
-   bottom margin is 75px
-   left margin is 100px

**margin-top**	Marge extérieure du haut de l'élément.
**margin-right**	Marge extérieure de droite de l'élément.
**margin-left**	Marge extérieure de gauche de l'élément.
**max-height**	Hauteur maxi de l'élément.
**min-height**	Hauteur mini de l'élément.
**max-width**	Largeur maxi de l'élément.
**min-width**	Largeur mini de l'élément.
**overflow-x**	Présence/absence de l'ascenseur droit (Explorer seulement)
**overflow-y**	Présence/absence de l'ascenseur bas (Explorer seulement)
**overflow**	Présence/absence des ascenseurs.
overflow:  visible; hidden auto
**padding**	Marges intérieures de l'élément

padding: 25px 50px 75px 100px;**

-   top padding is 25px
-   right padding is 50px
-   bottom padding is 75px
-   left padding is 100px

**padding-top**	Marge intérieure haute de l'élément
**padding-left**	Marge intérieure gauche de l'élément
**padding-right**	Marge intérieure droite de l'élément
**padding-bottom**	Marge intérieure basse de l'élément
**position**	Positionnement de l'élément.
position : relative ;
position:  absolute;  
top:  80px;  
right:  0;
**right**	Position droite de l'élément.
**text-align**	Détermine l'alignement horizontal du texte à l'intérieur d'un élément.
**top**	Position supérieure de l'élément.
**vertical-align**	Alignement vertical de l'élément.
**width**	Définit la largeur de l'élément
**z-index**	Définit l'ordre de superposition des éléments (dessus/dessous).

## Table (tableaux)

Ces propriétés ne s'appliquent qu'aux éléments de type < Table> et à leurs sous-éléments (caption, td, etc.)

border-collapse	Mode d'encadrement des cellules adjacentes.
**border-spacing**	Espacement entre deux traits de cellules adjacentes.
**caption-side**	Emplacement du titre des tableaux.
**empty-cells**	Mode d'affichage des cellules vides.
**speak-header**	Mode de restitution des titres de tableaux.
**table-layout**	Mode de calcul des largeurs de colonnes et de tableaux.


## Texte et caractères

Cette famille regroupe toutes les propriétés permettant d'agir sur le texte.

**color**	Couleur de l'avant plan (texte, par exemple).
direction	Sens d'écriture.
**font**	Ensemble des propriétés concernant les caractères.
**font-family**	Police de caractères.
**font-size**	Taille des caractères.
**font-size-adjust**	Hauteur des lignes de texte.
**font-stretch**	Etirement ou compression des caractères.
**font-style**	Mise en italique.
**font-variant**	Mise en petites capitales.
**font-weight**	Mise en gras ou extra-gras (extra-bold).
**letter-spacing** 	Espacement des lettres.
letter-spacing:  3px;
**line-break**	Contrôle les règles qui régissent le saut de ligne pour un texte en japonais.
**line-height**	Hauteur de ligne
**text-align**	Détermine l'alignement horizontal du texte à l'intérieur d'un élément.
text-align:  center;
**text-align-last**	Détermine l'alignement horizontal de la dernière ligne de texte dans un cadre de l'élément (Explorer seulement).
**text-autospace**	Détermine l'espacement entre les caractères (langues asiatiques - Explorer seulement).
**text-decoration**	Soulignement ou rayure du texte.
text-decoration:  none;
**text-indent**	Indentation du texte.
text-indent:  50px;
**text-justify**	Justification du texte.
**text-kashida-space**	Concerne le texte arabe inclus dans un élément de bloc (Explorer seulement).
**text-overflow**	Détermine s'il faut afficher le contenu débordant d'un cadre plein sous forme de points de suspension (...) à la fin de la ligne
**text-shadow**	Définit les effets d'ombre à appliquer au texte de l'élément.
text-shadow:  3px 2px red;
**text-transform**	Contrôle la capitalisation (majuscules/minuscules) du texte d'un élément.
text-transform:  uppercase;
**text-underline-position**	Position du texte par rapport au soulgnement (langues asiatiques - Explorer seulement).
**unicode-bidi**	Détermine l'incorporation du texte bidirectionnel avec la propriété de style direction (langues asiatiques - Explorer seulement).
**vertical-align**	Alignement vertical de l'élément.
**unicode-bidi**	Détermine l'incorporation du texte bidirectionnel avec la propriété de style direction (langues asiatiques - Explorer seulement).
**white-space**	Gestion des espaces multiples et des retours chariot.
**word-break**	Détermine le style de césure de mot (langues asiatiques - Explorer seulement).
**word-wrap**	Détermine le style de renvoi à la ligne pour les éléments de niveau bloc, les éléments incorporés de taille spécifique ou les éléments positionnés (Explorer seulement).
**writing-mode**	Progression du contenu texte dans l'élément (langues asiatiques - Explorer seulement).

## Anchor Pseudo-classes
/* unvisited link */  
a:link {  
color:  #FF0000;  
}  
  
/* visited link */  
a:visited {  
color:  #00FF00;  
}  
  
/* mouse over link */  
a:hover {  
color:  #FF00FF;  
}  
  
/* selected link */  
a:active {  
color:  #0000FF;  
}
## Les unités
**Unités absolues**
Toutes les unités absolues sont équivalentes selon le rapport suivant : 1 in = 2,54 cm = 25,4 mm = 72 pt = 6 pc.

**cm**	Le centimètre
**in**	Le pouce (en anglais « inch ») correspondant à 2,54 cm
**mm**	Le millimètre
**pt**	Le point. Correspond à un soixante-douxième d'inch.
**pc**	Le pica (correspondant à 12 pt)

**Unités relatives**
**em**	Unité relative à la taille de police de l'élément.
1 em équivaut à 100% de cette taille.

**ex**	Unité relative à la hauteur de la minuscule de l'élément. Seule exception à cette règle : lorsque la propriété font-size est définie, elle se rapporte à la hauteur de la minuscule de l'élément parent.

**px**	Le pixel. Il s'agit d'une unité dont le rendu dépend de la résolution du périphérique d'affichage
%	Le pourcentage est une unité relative à la taille de l'élément ou de son parent.

## 3 modes d'affichage pour les éléments HTML

Par défaut, les éléments HTML sont affichés selon l'un des modes suivants :

**1- Bloc / block**

![éléments superposés](http://www.css-faciles.com/illustrations/bloc-sous.gif)Occupe toute la largeur disponible. Lorsque 2 éléments blocs se suivent dans une page, ils sont positionnés (par défaut) l'un  **sous**  l'autre.

_Exemple typique d'élément bloc : l'élément <p> (le paragraphe)._

**2- En-ligne / inline**

![éléments côte à côte](http://www.css-faciles.com/illustrations/inline-cote.gif)N'occupe que la largeur indispensable à l'affichage du contenu et ne provoque pas de retour à la ligne. Lorsque 2 éléments en-ligne se suivent dans une page, ils sont positionnés l'un  **à côté** l'autre (si la largeur de page le permet).

_Exemple typique d'élément en-ligne : l'élément <img> (image)._

**3- Invisible / not displayed**

![élément invisible](http://www.css-faciles.com/illustrations/rien.gif)Certains éléments ne servent qu'à apporter des informations invisibles pour l'internaute.

_Exemple typique d'élément non affiché : l'élément <meta>._