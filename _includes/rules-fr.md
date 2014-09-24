# Les Échecs Masqués

## Les règles

### Introduction

Les Échecs Masqués sont une variante du jeu d'échecs. Il est nécessaire d'avoir une bonne connaissance des [règles](http://fr.wikipedia.org/wiki/%C3%89checs#R.C3.A8gles_du_jeu) de ce dernier pour pouvoir jouer aux Échecs Masqués, à tel point qu'une partie de jeu d'échecs masqués où toutes les pièces sont dévoilées ne diffèrent plus d'une partie d'échecs classique.

Nous ne reprendrons pas ici les règles du jeu d'échecs, nous indiquerons seulement celles qui sont spécifiques aux Échecs Masqués, soit qu'elles modifient, soit qu'elles s'ajoutent aux premières.

### Définitions préliminaires

D'autres éléments sont à définir plus loin, mais certains doivent l'être pour commencer. Les voici.

#### Pièce masquée et figure

Une pièce est dite **masquée** lorsque seul son propriétaire en connait la **figure**.
Dans les échecs classiques, une pièce et sa figure ne se distinguent pas : un cavalier est un cavalier, une tour est une tour, il n'y pas de quoi discuter. Dans les échecs masqués, il en va autrement. Ainsi, lorsqu'un cavalier est masqué, seul son propriétaire sait qu'il s'agit d'un cavalier. L'adversaire, lui, ne voit qu'une pièce masquée.

#### Dévoilement et pièce dévoilée

Une pièce est **dévoilée** lorsque sa figure est connue de tous. Le **dévoilement** est l'acte par lequel sa figure est rendue publique.

#### Bataille

Il y a **bataille** lorsqu'une pièce masquée est attaquée. Il y a bataille masquée lorsqu'une bataille est engagée par une pièce masquée.

#### Force des pièces

Lors de la bataille, un facteur déterminant peut être la **force** des figures. Celles-ci correspondent à ce qui est habituellement admis dans les échecs classiques et utilisé pour calculer les points des joueurs. De la plus faible à la plus forte, voici l'ordre des figures :

* le Pion
* le Cavalier et le Fou, *qui ont la même force*
* la Tour
* la Dame
* le Roi

#### Prise sans dévoilement

Lorsqu'une pièce masquée est prise, elle peut l'être avec ou sans dévoilement selon la situation. **Si une pièce est prise sans dévoilement, c'est son propriétaire qui la retire du jeu sans en faire connaître la figure**, et non son adversaire comme il est d'usage aux échecs ordinaires.

### Mise en place du jeu

La mise en place est un étape importante du jeu et déterminante pour la suite. En effet, toutes les pièces sont encore masquées et chacun des adversaires peut les placer où bon lui semble sur ses deux lignes de départ (1 et 2 pour les blancs, 7 et 8 pour les noirs). Ainsi le Roi blanc peut très bien être en position D2.

### Mouvements des pièces masquées

Tant qu'une pièce est masquée son mouvement est en tous points celui d'un pion :

* elle peut avancer de une ou deux cases en avant depuis sa position initiale,
* elle peut avancer de une seule case en avant sur les autres positions,
* elle peut prendre en diagonale,
* elle peut prendre un autre pion ou une autre pièce masquée en passant lorsque celle-ci quitte sa position initiale en avançant de deux cases mais uniquement au tour suivant (règle de la prise en en passant).

Il est à noter que la prise en passant sur une pièce masquée donne lieu à une bataille.

Arrivée à la huitième ligne, une pièce masquée *ne peut pas* être convertie en n'importe quelle pièce, à moins qu'elle ne soit d'abord dévoilée comme pion, mais rien n'oblige à ce qu'une pièce masquée arrivée à la huitième ligne soit dévoilée -- elle reste alors simplement immobile jusqu'à son dévoilement.

**Une pièce masquée ne peut donc pas se déplacer selon les règles de sa figure.**

### Dévoilements

Une pièce peut être dévoilée dans plusieurs situations.

#### Par le joueur

Le joueurpeut décider de dévoiler sa pièce *avant* de la déplacer. Sa figure est alors connue de tous, et la pièce peut se déplacer comme elle le fait aux échecs ordinaires.

#### Par mise en échec de la pièce masquée

Lorsque l'adversaire, à la suite de son dernier coup, menace une pièce masquée, il peut déclarer un **échec au masque** (il prononce les mots à haute voix) en indiquant du doigt *sans la toucher* la pièce masquée qu'il menace. Le joueur a alors le choix : soit il dévoile la pièce masquée, soit il la laisse masquée, et c'est alors à lui de jouer. *S'il la laisse masquée, alors l'adversaire peut au coup suivant prendre la pièce masquée qu'il a mise en échec sans engager une bataille, mais également **sans la dévoiler**.*

Il ne peut y avoir de mise en échec que d'une seule pièce masquée lors d'un tour.

#### Par mise en échec et mat de la pièce masquée

Lorsque l'adversaire, à la suite de son dernier coup, menace une pièce masquée de telle sorte à ce qu'il soit impossible à son propriétaire de la soustraire à cette menace dès le coup suivant, l'adversaire peut alors déclarer un **échec et mat au masque** (là aussi, il prononce les mots à haute voix) en indiquant du doigt *sans la toucher* la pièce masquée qu'il menace. Le propriétaire n'a alors pas le choix : il *doit* dévoiler la pièce en question. S'il s'agit du Roi, il a naturellement perdu.

### Bataille
Il y a bataille lorsque l'adversaire tente de prendre une pièce masquée. Contrairement aux échecs classiques, la prise d'une pièce masquée ne va pas de soit, l'idée étant qu'une pièce forte maquillée en une pièce faible est succeptible d'offrir plus de résistance qu'attendu...

La bataille constitue un mouvement en elle-même et compte comme tel.

Lorsqu'il souhaite prendre une pièce masquée, l'adversaire déclare une **bataille** (il prononce le mot à haute voix) en indiquant, sans les toucher, d'abord sa pièce attaquante, puis la pièce attaquée. Ne peuvent être engagées dans une bataille qu'une seule pièce attaquante et une pièce attaquée.

Deux situations sont alors possibles : soit la pièce attaquante est déjà dévoilée, il s'agit alors d'une **bataille simple** ; soit elle est masquée, il s'agit alors d'une **bataille masquée**.

#### Bataille simple

Lors de la bataille simple, le propriétaire de la pièce attaquée a le choix entre dévoiler sa pièce ou non.

S'il choisit de ne pas la dévoiler, il y a alors *prise sans dévoilement* et il retire lui-même sa pièce du jeu tandis que l'adversaire place sa propre pièce attaquante sur la position qui était celle de la pièce attaquée.

S'il choisit de la dévoiler, plusieurs situations sont possibles :

* soit la pièce qu'il dévoile est moins forte que la pièce attaquante : alors l'adversaire prend cette pièce et place sa pièce attaquante sur sa position,
* soit la pièce qu'il dévoile est plus forte que la pièce attaquante : alors l'attaque échoue et il prend la pièce attaquante sans déplacer la sienne,
* soit les pièces sont de même force : l'attaque est alors repoussée, les deux pièces conservent leur position pour ce tour.

#### Bataille masquée

##### Déclaration

Une pièce masquée attaque une pièce masquée. L'ignorance est alors des deux côtés et il s'agit de la situation la plus caractéristique des Échecs Masqués.

Il n'est pas nécessaire à l'attaquant de prononcer "Bataille" dans ce cas. Mais il doit **annoncer** une figure, supposée être celle ce la pièce attaquante, en même temps qu'il l'indique du doigt, avant de dire "attaque le masque" en indiquant la pièce attaquée sans la toucher. La figure annoncée n'est pas nécessairement la figure réelle, on parle alors de **bluff**. On peut **bluffer à la hausse** en anonçant une force supérieure à celle réelle de la figure, ou, à l'inverse, **bluffer à la baisse**.

Attaqué et attaquant se trouvent alors en position d'**annonceur**, chacun à son **tour d'annonce**.

##### Tour d'annonce

L'annonceur peut prendre plusieurs décisions :

* soit il décide de laisser prendre sa pièce *sans dévoilement*, auquel cas il la retire du jeu, on dit alors qu'il se **couche**. Si l'anonceur était l'attaqué, alors l'attaquant place sa pièce sur la position libérée, sinon, il n'y a pas d'autre mouvement.
* soit il annonce une figure plus élevée que l'annonceur précédent, on dit alors qu'il **relance**, et le tour d'annonce passe à l'adversaire,
* soit il décide de dévoiler sa pièce, et deux situations sont possibles :
	* soit il s'agit d'un pion, celui-ci est alors pris par l'adversaire sans que lui-même ait besoin de dévoiler sa pièce. Si l'adversaire est l'attaquant, alors sa pièce prend la position libérée,
	* soit il s'agit d'une autre pièce, alors l'adversaire doit dévoiler sa propre pièce et là encore plusieurs situations sont possibles :
		* soit la pièce de l'attaquant est plus forte que la pièce de l'attaqué, alors la pièce de l'attaqué est retirée du jeu et la pièce de l'attaquant prend sa position,
		* soit la pièce de l'attaqué est plus forte que celle de l'attaquant, alors la pièce de l'attaquant est retirée du jeu, mais la pièce de l'attaqué conserve sa position,
		* soit les deux pièces sont de même force, et là, une dernière fois, plusieurs situations sont possibles :
			* s'il n'y a eu aucun *bluff à la hausse*, l'attaque est repoussée et les deux pièces conservent leur position,
			* s'il y a eu *bluff à la hausse*, la pièce du dernier anonceur est retirée du jeu. S'il s'agit de l'attaqué, la pièce de l'attaquant prend la position libérée.

### Le Roque

La règle du Roque reste presque inchangée. Cela implique que le joueur voulant effectuer le Roque ait disposé dès la mise en place du jeu le Roi et la Tour à leurs positions habituelles. S'il ne l'avait pas fait, il a renoncé à cette possibilité de Roque.

La seule modification est la suivante : les échecs ordinaires prévoient que le Roque ne puisse avoir lieu si le Roi est en échec. Aux Échecs Masqués, il est possible de roquer lorsque le Roi est en échec *à condition qu'il soit encore masqué au moment du Roque.*

Il est par ailleurs évident que le Roque provoque le dévoilement des deux pièces impliquées dans le mouvement.

### Fin de partie

Victoire et défaite sont les mêmes qu'aux échecs, mais il est à remarquer qu'un Roi peut très bien avoir été perdu sans avoir été dévoilé. Dans ce cas, la partie continue jusqu'à ce que:

* le Roi de l'adversaire ait été mis échec et mat, auquel cas on peut parler (ou pas) de **victoire sans Roi**
* toutes les pièces du joueur qui a perdu le Roi masqué ait été dévoilées, on parle de **défaite sans Roi**
* le Roi de l'adversaire ait été mis pat, auquel cas il y a match nul.

Une victoire sans Roi a la même valeur qu'un échec et mat.

Une fois la partie terminée, les joueurs *peuvent* dévoiler leurs pièces, mais ils n'y sont en aucun cas contraints.


