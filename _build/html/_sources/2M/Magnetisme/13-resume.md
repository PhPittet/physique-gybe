# Résumé de la section

## [Aimants](chap:aimants)
- Le magnétisme est un sujet qui comprend les propriétés des aimants, l'effet de la force magnétique sur les charges et les courants en mouvement et la création de champs magnétiques par les courants.
- Il existe deux types de pôles magnétiques, appelés pôle nord magnétique et pôle sud magnétique.
- Les pôles nord magnétiques sont ceux qui sont attirés vers le pôle nord géographique de la Terre.
- Comme les pôles se repoussent et les pôles différents s'attirent.
- Les pôles magnétiques se produisent toujours par paires de nord et de sud---il n'est pas possible d'isoler les pôles nord et sud.

## [Ferroaimants et électroaimants](chap:electroaimants)
- Les pôles magnétiques se produisent toujours par paires de nord et de sud---il n'est pas possible d'isoler les pôles nord et sud.
- Tout magnétisme est créé par le courant électrique.
- Les matériaux ferromagnétiques, tels que le fer, sont ceux qui présentent de forts effets magnétiques.
- Les atomes des matériaux ferromagnétiques agissent comme de petits aimants (en raison des courants à l'intérieur des atomes) et peuvent être alignés, généralement dans des régions de taille millimétrique appelées domaines.
- Les domaines peuvent croître et s'aligner à plus grande échelle, produisant des aimants permanents. Un tel matériau est magnétisé, c'est-à-dire induit à être magnétique.
- Au-dessus de la température de Curie d'un matériau, l'agitation thermique détruit l'alignement des atomes et le ferromagnétisme disparaît.
- Les électroaimants utilisent des courants électriques pour créer des champs magnétiques, souvent aidés par des champs induits dans les matériaux ferromagnétiques.

## [Champs magnétiques et lignes de champ magnétique](chap:champs_magn)
Les champs magnétiques peuvent être représentés de manière picturale par des lignes de champ magnétique, dont les propriétés sont les suivantes :

1. Le champ est tangent à la ligne de champ magnétique.
2. L'intensité du champ est proportionnelle à la densité de la raie.
3. Les lignes de champ ne peuvent pas se croiser.
4. Les lignes de champ sont des boucles continues.

## [Force exercée sur une charge en mouvement dans un champ magnétique](chap:Lorentz)

- Les champs magnétiques exercent une force sur une charge en mouvement *q*, dont l'amplitude est
:::{math}
F = \text{qvB}\ \text{sin}\ \theta
:::

où $\theta$ est l'angle entre les directions de $v$ et $B$.

- L'unité SI pour l'intensité du champ magnétique $B$ est le tesla (T), qui est lié à d'autres unités par
:::{math}
1\ T = \frac{\text{1 N}}{C \cdot \text{m/s}} = \frac{\text{1 N}}{A \cdot m}
:::

- La *direction* de la force sur une charge en mouvement est donnée par la règle de la main droite 1 : *Pointez le pouce de la main droite dans la direction de $v$, les doigts dans la direction de $B$, et une perpendiculaire à la paume pointe dans la direction de $F$*.
- La force est perpendiculaire au plan formé par $v$ et $B$. Comme la force est nulle si $v$ est parallèle à $B$, les particules chargées suivent souvent les lignes de champ magnétique plutôt que de les traverser.

- La force magnétique peut fournir une force centripète et provoquer le déplacement d'une particule chargée dans une trajectoire circulaire de rayon
:::{math}
$r = \frac{mv}{qB}
:::

où $v$ est la composante de la vitesse perpendiculaire à $B$ pour une particule chargée de masse $m$ et de charge $q$.

## [L'effet Hall](chap:Effet_Hall)

- L'effet Hall est la création d'une tension $\varepsilon$, connue sous le nom de force électromotrice de Hall, aux bornes d'un conducteur porteur de courant par un champ magnétique.
- La force électromotrice de Hall est donnée par
:::{math}
\varepsilon = Blv\ (B,\ v,\ \text{et}\ l,\ \text{perpendiculairement mutuelle})
:::

pour un conducteur de largeur $l$ à travers lequel les charges se déplacent à une vitesse $v$.

## [Force magnétique sur un conducteur porteur de courant](chap:Laplace)=

- La force magnétique sur les conducteurs porteurs de courant est donnée par
:::{math}
F = I\cdot l\cdot B\sin\thêta
:::

où $I$ est le courant, $l$ est la longueur d'un conducteur droit dans un champ magnétique uniforme $B$, et $\theta$ est l'angle entre $I$ et $B$. La force suit la règle de la main droite avec le pouce dans la direction de $I$.

## 22.9 Champs magnétiques produits par les courants : loi d'Ampère

- L'intensité du champ magnétique créé par le courant dans un long fil droit est donnée par
:::{math}
B = \frac{\mu_{0}I}{2\pi r}(\text{fil droit long})
:::

où $I$ est le courant, $r$ est la distance la plus courte au fil, et la constante $\mu_{0} = 4\pi\cdot 10^{-7}\,\text{T}\cdot \text{m/A}$ est la perméabilité de l'espace libre.

- La direction du champ magnétique créé par un long fil droit est donnée par la règle de la main droite 2 : *Pointez le pouce de la main droite dans le sens du courant, et les doigts s'enroulent dans la direction des boucles de champ magnétique* créées par celui-ci.
- Le champ magnétique créé par le courant suivant n'importe quel chemin est la somme (ou intégrale) des champs dus aux segments le long du chemin (amplitude et direction comme pour un fil droit), ce qui donne une relation générale entre le courant et le champ connue sous le nom de loi d'Ampère.
- L'intensité du champ magnétique au centre d'une boucle circulaire est donnée par
:::{math}
B = \frac{\mu_{0}I}{2R}\qquad (\text{au centre de la boucle})
:::
où $R$ est le rayon de la boucle. Cette équation devient $B = N\mu_{0}I/(2R)$ pour une bobine plate de $N$ boucles. La règle de la main droite 2 donne la direction du champ autour de la boucle. Une longue bobine s'appelle un solénoïde.

- L'intensité du champ magnétique à l'intérieur d'un solénoïde est
:::{math}
B = N\frac{\mu_{0}I}{L}\qquad (\text{à l'intérieur d'un solénoïde})
:::

où $L$ est la longueur du solénoïde et $N$ est le nombre de boucles du solénoïde. Le champ à l'intérieur est très uniforme en magnitude et en direction.

## 22.10 Force magnétique entre deux conducteurs parallèles

- La force entre deux courants parallèles $I_{1}$ et $I_{2}$, séparés par une distance $r$, a une amplitude par unité de longueur donnée par
:::{math}
\frac{F}{l} = \frac{\mu_{0}I_{1}I_{2}}{2\pi r}
:::

- La force est attractive si les courants sont dans le même sens, répulsive s'ils sont dans des directions opposées.

## 22.11 Autres applications du magnétisme

- Les champs électriques et magnétiques croisés (perpendiculaires) agissent comme un filtre de vitesse, donnant des forces égales et opposées sur toute charge avec une vitesse perpendiculaire aux champs et de magnitude
:::{math}
v = \frac{E}{B}
:::
