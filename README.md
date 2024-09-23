# Cycle Éco-Planétaire


## Par Keven Malric

### Idée derrière l'oeuvre
Le principe de l'oeuvre: **Cycle Éco-Planétaire** est de critiquer un manque de sens de la routine industrielle/humaine. Par l'immersion, de la réalité augmentée, **Cycle Éco-Planétaire** plonge ses participant dans un univers desertique ou il n'y a aucune végétation et ou le seul moyen d'avancer est de creusé vainment les sables pour des richesses temporaires. L'oeuvre en réalité virtuelle cherche à choquer par manque de progrès du point de vue de l'histoire afin de démontré la futilité des actions commises par l'avarice et l'envie humaine qui détruit notre environnement.

#### meta

Est utilisée pour inclure des métadonnées, comme des descriptions ou des informations relatives au contenu de la page, sans les afficher directement aux utilisateurs.

```html

<meta name="description" content="Modèle docsify pour publication classique">

```

#### title
Définit le titre de la page qui s'affiche dans l'onglet du navigateur et est utilisé par les moteurs de recherche comme le titre principal dans les résultats de recherche.

```html
<title>Modèle docsify pour publication classique</title>
```




#### window.$docsify 

##### name

Titre de la page affiché dans la barre de coté

```html
name: 'Modèle Docsify Classique',
```

##### repo

Lien vers le repository git du projet à documenter, cliquable depuis l'icone dans la barre de coté

```html
repo: 'https://github.com/gllmAR/docsify-modele-classique',
```


#### CSS (optionnelle)

Source et lien vers style CSS lié  [gllmAR/docsify-simple-style](https://github.com/gllmAR/docsify-simple-style/)

###Oeuvre


```mermaid
graph TD;
    personnage-->apprenti?;
    apprenti?-->oui;
    apprenti?-->non;
    oui-->creuse;
    non-->personnage;
    creuse-->visiteur;
    visiteur-->parle?;
    parle?-->salut;
    parle?-->non2;
    salut-->trésort;
    trésort-->argent;
    argent-->village;
    village-->fête;
    fête-->dors;
    dors-->creuse3;
    creuse3-->serpent;
    serpent-->mord;
    mord-->meurt;
    meurt-->personnage;
    non2-->continue;
    continue-->enfant;
    enfant-->tutel;
    tutel-->vieux;
    vieux-->choix
    choix-->vieillard;
    choix-->jeune;
    vieillard-->mort;
    mort-->personnage;
    jeune-->personnage2;
    personnage2-->creuse;
    

```


