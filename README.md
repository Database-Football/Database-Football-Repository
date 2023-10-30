# Bienvenue dans le README de notre organisation _UniFoot_

###### <p> Dans ce README, nous allons présenter et expliquer le projet qui nous a demander tant d'effort et de sueur : _DataBase FootBall_

# <u> 1 - Objectif de _Database FootBall_</u>

_Database FootBall_ est un site web centré sur le football visant à rendre accessible au plus grand public les données portant sur les joueurs professionnels évoluant sur le continent européen.

# <u> 2 - Outils utilisés </u>

Pour la réalisation de ce projet, nous avons utilisés un certain nombre d'outils :
- le _langage XML_pour la création d'un document XML,
- une _**DTD**[^1]_ représentant la grammaire d'un document XML et
- le _langage CSS_ pour réaliser une feuille de style CSS pour la mise en forme de notre site web.

# <u> 3 - DTD </u>
La DTD, est un fichier Q7-DTD, modélisant une partie des informations portant sur le football.

Le fichier est composé de :
- un élément racine **foot**  qui renferme un élément **glossaire** (donnée facultative et répétable),
- au moins un élément **club** obligatoire,
- un élément **mot**(texte) obligatoire contenu dans l'élément **glossaire**
- l’élément club renfermant les éléments suivants : 
    - **nom_club** (texte), 
    - **date_Creation**(texte) , 
    - **bilanCO2** (texte), 
    - **nom_Terrain** (texte) et 
    - **nom_Pays** (texte).

Par ailleurs, certains des éléments cités comporte des attributs. L’élément **mot** porte un attribut def obligatoire et l’élément <glossaire> porte un attribut auteur facultatif.

<p align="center">
<img src=/images/fichier_DTD.jpg width="100px>
</p>

*Image du fichier DTD*


# <u> 4 - XML </u>

La section XML renferme la création de deux fichiers : le Q8a-XML.xml et le Q8b-XML.xml respectant le modèle DTD défini précédemment. 

Le _Q8a-XML.xml_ présente un jeu de données prises aléatoirement. Il renferme deux éléments glossaires ( donnée facultative et répétable) le premier portant un attribut facultatif auteur de valeur “Binôme Daniela David” à l’inverse du second élément glossaire ne portant aucun attribut. 

Nous avons ensuite l’élément <club> qui comporte les éléments **nom_Club**, **date_Creation**, **bilanCO2**, **nom_Terrain**, **nom_Pays** avec un attribut def obligatoire comme spéficié dans la DTD. 

Le second fichier  Q8b-XML.xml respecte la grammaire définie par notre DTD avec un élement **glossaire** et plusieurs éléments **club** (obligatoire et répétable).


# <u> 5 - CSS </u>

Dans cette section, nous avons créé deux feuilles de style CSS: 
1. _Q10a-XML.css_ pour la mise en forme de nos fichiers XML définis dans les sections précédentes et 
2. _Q10b-HTML.css_ pour le fichier _Q9-HTML.html_ (notre site web).

	Dans le fichier  Q10a-XML.css, nous y avons mis des sélecteurs qui sont les éléments utilisées dans les documents Xml avec des propriétés pour les caractériser comme le montre l’exemple suivant où on a préféré mettre un fond de couleur bisque à l’arrière plan de notre document Xml: foot { background-color: bisque; }

Par ailleurs, nous avons utilisé dans le fichier _Q10b-XML.css_ des sélecteurs qui sont des éléments du document XHTML muni d’une DTD spéficique.




Dans le texte ordinaire [] vous pouvez facilement placer des notes de bas de page [^2]
[^1]: **DTD** : 
[^2]: **Note de page de page** peut aussi être *formatée*.
Et celles-ci comprennent même plusieurs lignes