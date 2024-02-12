(chap:Laplace)=
# Force magnétique sur un conducteur porteur de courant

## Objectifs d'apprentissage

À la fin de cette section, vous serez en mesure de :

- Décrire les effets d'une force magnétique sur un conducteur porteur de courant.
- Calculer la force magnétique sur un conducteur porteur de courant.

Étant donné que les charges ne peuvent généralement pas s'échapper d'un conducteur, la force magnétique sur les charges se déplaçant dans un conducteur est transmise au conducteur lui-même.

Figure 22.29 Le champ magnétique exerce une force sur un fil porteur de courant dans une direction donnée par la règle de droite 1 (la même direction que celle des charges mobiles individuelles). Cette force peut facilement être assez grande pour déplacer le fil, car les courants typiques sont constitués d'un très grand nombre de charges mobiles.

Nous pouvons dériver une expression de la force magnétique sur un courant en prenant une somme des forces magnétiques sur des charges individuelles. (Les forces s'additionnent parce qu'elles sont dans la même direction.) La force exercée sur une charge individuelle se déplaçant à la vitesse de dérive $v_{d}$ est donnée par $F = q\cdot v_{d}\cdot B\ \sin \theta$. Si $B$ est uniforme sur une longueur de fil $l$ et nulle ailleurs, la force magnétique totale sur le fil est alors $F = (q\cdot v_{d}\cdot B\ \sin \theta)(N)$, où $N$ est le nombre de porteurs de charge dans la section de fil de longueur $l$. Maintenant, $N = \text{nV}$, où $n$ est le nombre de porteurs de charge par unité de volume et $V$ est le volume de fil dans le champ. En notant que $V = \text{Al}$, où $A$ est l'aire de la section transversale du fil, alors la force exercée sur le fil est $F = (q\cdot v_{d}\cdot B\ \sin \theta)(\text{nAl})$. Rassembler les termes,

$$F = nqAv_{d}lB\sin \theta.$$

22.15

Parce que $nqAv_{d} = I$ (voir [Current]),

$$F = IlB\sin\theta$$

22.16

est l'équation de *la force magnétique sur une longueur* $l$ *de fil transportant un courant* $I$ *dans un champ magnétique uniforme* $B$, comme le montre la [Figure 22.30]. Si nous divisons les deux côtés de cette expression par $l$, nous trouvons que la force magnétique par unité de longueur de fil dans un champ uniforme est $\frac{F}{l} =IB\sin \theta$. La direction de cette force est donnée par RHR-1, avec le pouce dans la direction du courant $I$. Ensuite, avec les doigts dans la direction de $B$, une perpendiculaire à la paume pointe dans la direction de $F$, comme dans [Figure 22.30].

Figure 22.30 La force exercée sur un fil porteur de courant dans un champ magnétique est $F =IB \sin \theta$. Sa direction est donnée par RHR-1.

### Exemple 22.4
:::::{admonition} Exemple_résolution
:class: exores
Calculer la force exercée sur le fil représenté dans la [Figure 22.29], étant donné $B = 1.5\,T$, $l = 5.00 cm$ et $I =20\,A$.
::::{admonition} *stratégie*
:class: dropdown strategie
La force peut être trouvée avec l'information donnée en utilisant $F = IlB \sin \theta$ et en notant que l'angle $\theta$ entre $I$ et $B$ est $90°$, de sorte que $\sin \theta = 1$.
::::
::::{admonition} *solution*
:class: dropdown solution
L'entrée des valeurs données dans $F = ILB \sin \theta$ donne

$$F = IlB \sin \theta = \left( 20.0\,A\right)\left( 0.0500\,m \right)\left( 1.50\,T \right)(1)\text{.} $$

22.17

Les unités de tesla sont $1\,T = \frac{N}{A \cdot m}$ ; ainsi

$$F = 1.50\,N$$

22.18
::::
::::{admonition} *discussion*
:class: dropdown discussion
Ce grand champ magnétique crée une force importante sur une petite longueur de fil.
::::
:::::

La force magnétique sur les conducteurs porteurs de courant est utilisée pour convertir l'énergie électrique en travail. (Les moteurs en sont un excellent exemple --- ils utilisent des boucles de fil et sont examinés dans la section suivante.) La magnétohydrodynamique (MHD) est le nom technique donné à une application intelligente où la force magnétique pompe des fluides sans déplacer de pièces mécaniques. (Voir [Figure 22.31].)

Figure 22.31 Magnétohydrodynamique. La force magnétique sur le courant qui traverse ce fluide peut être utilisée comme une pompe non mécanique.

Un champ magnétique puissant est appliqué à travers un tube et un courant traverse le fluide perpendiculairement au champ, ce qui entraîne une force sur le fluide parallèle à l'axe du tube, comme indiqué. L'absence de pièces mobiles le rend attrayant pour le déplacement d'une substance chaude chimiquement active, telle que le sodium liquide utilisé dans certains réacteurs nucléaires. Des cœurs artificiels expérimentaux testent cette technique de pompage du sang, contournant peut-être les effets néfastes des pompes mécaniques. (Les membranes cellulaires, cependant, sont affectées par les grands champs nécessaires à la MHD, ce qui retarde son application pratique chez l'homme.) La propulsion MHD pour les sous-marins nucléaires a été proposée, car elle pourrait être considérablement plus silencieuse que les moteurs à hélices conventionnels. La valeur dissuasive des sous-marins nucléaires repose sur leur capacité à se cacher et à survivre à une première ou une deuxième frappe nucléaire. Au fur et à mesure que nous démontons nos arsenaux d'armes nucléaires, la branche sous-marine sera la dernière à être mise hors service en raison de cette capacité (voir [Figure 22.32]). Les disques MHD existants sont lourds et inefficaces--- beaucoup de travail de développement est nécessaire.

Figure 22.32 Un système de propulsion MHD dans un sous-marin nucléaire pourrait produire beaucoup moins de turbulences que les hélices et lui permettre de fonctionner plus silencieusement. Le développement d'un sous-marin silencieux a été dramatisé dans le livre et le film The Hunt for Red October.

  [Actuel] : http://openstax.org/books/college-physics-2e/pages/20-1-current
  [Figure 22.30] : #import-auto-id1166991837003
  [Figure 22.29] : #import-auto-id1166991836288
  [Figure 22.31] : #import-auto-id1166991862057
  [Figure 22.32] : #import-auto-id1166991838446
