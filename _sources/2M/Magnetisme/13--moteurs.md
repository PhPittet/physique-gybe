# 22.8 Couple sur une boucle de courant : moteurs et compteurs

## Objectifs d'apprentissage

À la fin de cette section, vous serez en mesure de :

- Décrire le fonctionnement des moteurs et des compteurs en termes de couple sur une boucle de courant.
- Calculer le couple sur une boucle conductrice de courant dans un champ magnétique.

Les moteurs sont l'application la plus courante de la force magnétique sur les fils porteurs de courant. Les moteurs ont des boucles de fil dans un champ magnétique. Lorsque le courant passe dans les boucles, le champ magnétique exerce un couple sur les boucles, ce qui fait tourner un arbre. L'énergie électrique est convertie en travail mécanique. (Voir [Figure 22.33].)

! [][1]

Figure 22.33 Couple sur une boucle de courant. Une boucle de fil porteuse de courant attachée à un arbre en rotation verticale ressent des forces magnétiques qui produisent un couple dans le sens des aiguilles d'une montre, vu d'en haut.

Examinons la force exercée sur chaque segment de la boucle dans la [Figure 22.33] pour trouver les couples produits autour de l'axe de l'arbre vertical. (Cela conduira à une équation utile pour le couple sur la boucle.) Nous considérons que le champ magnétique est uniforme sur la boucle rectangulaire, qui a une largeur $w$ et une hauteur $l$. Tout d'abord, nous remarquons que les forces sur les segments supérieur et inférieur sont verticales et, par conséquent, parallèles à l'arbre, ne produisant aucun couple. Ces forces verticales sont égales en amplitude et de direction opposée, de sorte qu'elles ne produisent pas non plus de force nette sur la boucle. [Figure 22.34] montre des vues de la boucle d'en haut. Le couple est défini comme $\tau = \text{rF}\ \text{sin}\ \theta$, où $F$ est la force, $r$ est la distance du pivot à laquelle la force est appliquée et $\theta$ est l'angle entre $r$ et $F$. Comme on le voit dans la [Figure 22.34][](a), la règle de la main droite 1 donne que les forces sur les côtés sont égales en amplitude et de direction opposée, de sorte que la force nette est à nouveau nulle. Cependant, chaque force produit un couple dans le sens des aiguilles d'une montre. Puisque $r = w/2$, le couple sur chaque segment vertical est $(w/2)F\ \text{sin}\ \theta$, et les deux s'additionnent pour donner un couple total.

$\ta=\frac{w}{2}F\ \text{sin}\ \theta + \frac{w}{2}F\ \text{sin}\ \theta = \text{wF}\ \text{sin}\ \theta$

22.19

! [][2]

Figure 22.34 Vues de dessus d'une boucle porteuse de courant dans un champ magnétique. (a) L'équation du couple est calculée à l'aide de ce point de vue. Notez que la perpendiculaire à la boucle fait un angle $\theta$ avec le champ qui est le même que l'angle entre $w/2$ et $\mathbf{F}$. (b) Le couple maximal se produit lorsque $\theta$ est un angle droit et $\text{sin}\ \theta = 1$. (c) Le couple nul (minimum) se produit lorsque $\theta$ est égal à zéro et $\text{sin}\ \theta = 0$. (d) Le couple s'inverse une fois que la boucle tourne au-delà de $\theta = 0$.

Maintenant, chaque segment vertical a une longueur $l$ qui est perpendiculaire à $B$, de sorte que la force sur chacun est $F = \text{IlB}$. La saisie de $F$ dans l'expression pour les rendements de couple

$\tau = \text{wIlB}\ \text{sin}\ \theta.$

22.20

Si nous avons une boucle multiple de $N$ tours, nous obtenons $N$ fois le couple d'une boucle. Enfin, notez que l'aire de la boucle est $A = \text{wl}$ ; L'expression du couple devient

$\tau = \text{NIAB}\ \text{sin}\ \theta.$

22.21

Il s'agit du couple sur une boucle porteuse de courant dans un champ magnétique uniforme. On peut montrer que cette équation est valide pour une boucle de n'importe quelle forme. La boucle porte un courant $I$, a $N$ tours, chacun d'aire $A$, et la perpendiculaire à la boucle fait un angle $\theta$ avec le champ $B$. La force nette sur la boucle est nulle.

## Exemple 22.5 {#example-22.5 . Titre3Gris}

### Calcul du couple sur une boucle porteuse de courant dans un champ magnétique puissant {#calculating-couple-sur-une-boucle-porte-courant-dans-un-champ-magnétique-fort . Titre4Gris}

Trouvez le couple maximal sur une boucle carrée de 100 tours d'un fil de 10,0 cm sur un côté qui transporte 15,0 A de courant dans un champ de 2,00 T.

### Stratégie {#strategy . Titre4Gris}

Le couple sur la boucle peut être trouvé en utilisant $\tau = \text{NIAB}\ \text{sin}\ \theta$. Le couple maximal se produit lorsque $\theta = \text{90º}$ et $\text{sin}\ \theta = 1$.

### Solution {#solution . Titre4Gris}

Pour $\text{sin}\ \theta = 1$, le couple maximal est

$\tau_{\text{max}} = \text{NIAB}.$

22.22

La saisie de valeurs connues donne des résultats

! [équation multiligne ligne ligne 1 tau sous-maximum égal à la parenthèse gauche 100 parenthèse droite fois parenthèse gauche 15,0 cap A parenthèse droite fois parenthèse gauche 0,100 m super deux parenthèse droite fois parenthèse gauche deux période 00 cap T parenthèse droite ligne 2 Blanc égal à 30,0 majuscule N préfixe point m point]

22.23

### Discussion {#discussion . Titre4Gris}

Ce couple est suffisamment important pour être utile dans un moteur.

Le couple trouvé dans l'exemple précédent est le maximum. Au fur et à mesure que la bobine tourne, le couple diminue jusqu'à zéro à $\theta = 0$. Le couple *inverse* ensuite sa direction une fois que la bobine tourne au-delà de $\theta = 0$. (Voir [Figure 22.34][](d).) Cela signifie que, à moins que nous ne fassions quelque chose, la bobine oscillera d'avant en arrière autour de l'équilibre à $\theta = 0$. Pour que la bobine continue à tourner dans le même sens, nous pouvons inverser le courant lorsqu'il passe par $\theta = 0$ avec des interrupteurs automatiques appelés *balais*. (Voir [Figure 22.35].)

! [][3]

Figure 22.35 (a) Lorsque le moment cinétique de la bobine passe par $\theta = 0$, les balais inversent le courant pour maintenir le couple dans le sens des aiguilles d'une montre. (b) La bobine tournera continuellement dans le sens des aiguilles d'une montre, le courant s'inversant à chaque demi-tour pour maintenir le couple dans le sens des aiguilles d'une montre.

Les compteurs, tels que ceux des jauges de carburant analogiques d'une voiture, sont une autre application courante du couple magnétique sur une boucle porteuse de courant. [Figure 22.36] montre que la construction d'un compteur est très similaire à celle d'un moteur. Le mètre de la figure a ses aimants façonnés pour limiter l'effet de $\theta$ en rendant $B$ perpendiculaire à la boucle sur une large plage angulaire. Ainsi le couple est proportionnel à $I$ et non $\theta$. Un ressort linéaire exerce un contre-couple qui équilibre le couple produit par le courant. Cela rend la déviation de l'aiguille proportionnelle à $I$. S'il n'est pas possible d'obtenir une proportionnalité exacte, la lecture de la jauge peut être étalonnée. Pour produire un galvanomètre destiné à être utilisé dans les voltmètres et ampèremètres analogiques qui ont une faible résistance et répondent à de petits courants, nous utilisons une grande surface de boucle $A$, un champ magnétique élevé $B$ et des bobines à faible résistance.

! [][4]

Figure 22.36 Les compteurs sont très similaires aux moteurs, mais ne tournent que sur une partie d'un tour. Les pôles magnétiques de ce compteur sont façonnés pour maintenir constante la composante de $B$ perpendiculaire à la boucle, de sorte que le couple ne dépend pas de $\theta$ et que la déflexion contre le ressort de rappel n'est proportionnelle qu'au courant $I$.

  [Figure 22.33] : #import-auto-id1615457
  [1] : media/rId23.jpeg {width="3.4375in » height="1.9731244531933507in"}
  [Figure 22.34] : #import-auto-id2330568
  [2] : media/rId26.jpeg {width="6.25in » height="5.212498906386702in"}
  [équation multiligne ligne ligne 1 tau sous-maximum égal à la parenthèse gauche 100 parenthèse droite fois parenthèse gauche 15.0 cap Une parenthèse droite multipliée par la parenthèse gauche 0.100 m super deux parenthèse droite fois parenthèse gauche deux période 00 cap T parenthèse droite ligne 2 Blanc égal à 30.0 cap N préfixe point m point] : media/rId31.png {width="2.927083333333333335in » height="0.4270833333333333in"}
  [Figure 22.35] : #import-fig03
  [3] : media/rId34.jpeg {width="4.16666666666666667in » height="2.6in"}
  [Figure 22.36] : #import-auto-id2028294
  [4] : media/rId37.jpeg {width="3.64583333333333335in » height="2.227603893263342in"}
