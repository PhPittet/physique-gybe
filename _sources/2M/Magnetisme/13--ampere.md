# 22.9 Champs magnétiques produits par les courants : la loi d'Ampère

## Objectifs d'apprentissage

À la fin de cette section, vous serez en mesure de :

- Calculer le courant qui produit un champ magnétique.
- Utilisez la règle 2 de la main droite pour déterminer la direction du courant ou la direction des boucles de champ magnétique.

Quelle quantité de courant est nécessaire pour produire un champ magnétique important, peut-être aussi fort que le champ terrestre ? Les géomètres vous diront que les lignes électriques aériennes créent des champs magnétiques qui interfèrent avec la lecture de leur boussole. En effet, lorsqu'Oersted découvrit en 1820 qu'un courant dans un fil affectait l'aiguille d'une boussole, il n'avait pas affaire à des courants extrêmement importants. Comment la forme des fils transportant le courant affecte-t-elle la forme du champ magnétique créé ? Nous avons noté précédemment qu'une boucle de courant créait un champ magnétique similaire à celui d'un barreau magnétique, mais qu'en est-il d'un fil droit ou d'un toroïde (beignet) ? Comment la direction d'un champ créé par un courant est-elle liée à la direction du courant ? Les réponses à ces questions sont explorées dans cette section, ainsi qu'une brève discussion de la loi régissant les domaines créés par les courants.

## Champ magnétique créé par un long fil droit porteur de courant : règle de la main droite 2

Les champs magnétiques ont à la fois une direction et une amplitude. Comme indiqué précédemment, une façon d'explorer la direction d'un champ magnétique est d'utiliser des boussoles, comme le montre un long fil droit porteur de courant dans [Figure 22.37]. Les sondes à effet Hall peuvent déterminer l'amplitude du champ. Le champ autour d'un long fil droit se trouve être en boucles circulaires. La règle 2 de la main droite (RHR-2) émerge de cette exploration et est valable pour n'importe quel segment de courant ---*pointez le pouce dans la direction du courant, et les doigts s'enroulent dans la direction des boucles de champ magnétique* créées par celui-ci.

! [][1]

Figure 22.37 (a) Des boussoles placées près d'un long fil droit porteur de courant indiquent que les lignes de champ forment des boucles circulaires centrées sur le fil. b) La règle 2 de la main droite stipule que, si le pouce de la main droite pointe dans la direction du courant, les doigts s'enroulent dans la direction du champ. Cette règle est cohérente avec le champ mappé pour le long fil droit et est valable pour n'importe quel segment courant.

L'intensité du champ magnétique (magnitude) produite par un long fil droit porteur de courant est trouvée par l'expérience comme étant

$B = \frac{\mu_{0}I}{2\pi r}\ (\text{fil droit long}),$

22.24

où $I$ est le courant, $r$ est la distance la plus courte au fil, et la constante $\mu_{0} = 4\pi\, \times \,\text{10}^{- 7}\ T \cdot \text{m/A}$ est la perméabilité de l'espace libre. $(\mu_{0}$ est l'une des constantes de base de la nature. Nous verrons plus loin que $\mu_{0}$ est lié à la vitesse de la lumière.) Comme le fil est très long, l'amplitude du champ ne dépend que de la distance par rapport au fil $r$, et non de la position le long du fil.

## Exemple 22.6 {#example-22.6 . Titre3Gris}

### Calcul du courant qui produit un champ magnétique {#calculating-courant-qui-produit-un-champ-magnétique . Titre4Gris}

Trouvez le courant dans un long fil droit qui produirait un champ magnétique deux fois plus fort que celui de la Terre à une distance de 5,0 cm du fil.

### Stratégie {#strategy . Titre4Gris}

Le champ de la Terre est d'environ $5\text{.} 0 \times \text{10}^{- 5}\ T$, et donc ici $B$ dû au fil est considéré comme $1\text{.} 0 \times \text{10}^{- 4}\ T$. L'équation $B = \frac{\mu_{0}I}{2\pi r}$ peut être utilisée pour trouver $I$, puisque toutes les autres grandeurs sont connues.

### Solution {#solution . Titre4Gris}

En résolvant $I$ et en entrant des valeurs connues, on obtient

! [équation multiligne, ligne 1, majuscule I, égale à deux fois pi rB, divisé par mu, indice nul, égal à deux fois pi, parenthèse gauche, 5,0 fois 10, super négatif, deux fois m, parenthèse droite multipliée par parenthèse gauche, 1,0 fois 10, super négatif, quatre fois capuchon, T, parenthèse droite divisée par quatre fois pi fois 10, super négatif sept fois cap, point postfixe T, m barre oblique, majuscule A, ligne 2, blanc égal à 25, majuscule A, point]

22.25

### Discussion {#discussion . Titre4Gris}

Ainsi, un courant modérément important produit un champ magnétique important à une distance de 5,0 cm d'un long fil droit. Notez que la réponse n'est indiquée qu'à deux chiffres, puisque le champ de la Terre n'est spécifié qu'à deux chiffres dans cet exemple.

## La loi d'Ampère et autres

Le champ magnétique d'un long fil droit a plus d'implications que vous ne le pensez à première vue. *Chaque segment de courant produit un champ magnétique semblable à celui d'un long fil droit, et le champ total de n'importe quel courant de forme est la somme vectorielle des champs dus à chaque segment.* L'énoncé formel de la direction et de l'amplitude du champ dû à chaque segment est appelé la loi de Biot-Savart. Le calcul intégral est nécessaire pour additionner le champ d'un courant de forme arbitraire. Il en résulte une loi plus complète, appelée loi d'Ampère, qui relie le champ magnétique et le courant de manière générale. La loi d'Ampère, à son tour, fait partie des équations de Maxwell, qui donnent une théorie complète de tous les phénomènes électromagnétiques. Les considérations sur la façon dont les équations de Maxwell apparaissent à différents observateurs ont conduit à la théorie moderne de la relativité et à la prise de conscience que les champs électriques et magnétiques sont des manifestations différentes de la même chose. La plupart de ces éléments dépassent le cadre de ce texte, à la fois au niveau mathématique, qui nécessite du calcul, et dans la quantité d'espace qui peut lui être consacré. Mais pour l'étudiant intéressé, et en particulier pour ceux qui poursuivent dans la physique, l'ingénierie ou des activités similaires, approfondir ces questions révélera des descriptions de la nature à la fois élégantes et profondes. Dans ce texte, nous garderons à l'esprit les caractéristiques générales, telles que RHR-2 et les règles pour les lignes de champ magnétique énumérées dans [Champs magnétiques et lignes de champ magnétique], tout en nous concentrant sur les champs créés dans certaines situations importantes.

## Établir des connexions : Relativité {#making-connexions-relativité . Titre3Gris}

En entendant tout ce que nous savons d'Einstein, nous avons parfois l'impression qu'il a inventé la relativité à partir de rien. Au contraire, l'une des motivations d'Einstein était de résoudre les difficultés à savoir comment les différents observateurs perçoivent les champs magnétiques et électriques.

## Champ magnétique produit par une boucle circulaire porteuse de courant

Le champ magnétique près d'une boucle de fil porteuse de courant est représenté dans [Figure 22.38]. La direction et l'amplitude du champ magnétique produit par une boucle porteuse de courant sont complexes. RHR-2 peut être utilisé pour donner la direction du champ près de la boucle, mais la cartographie avec des boussoles et les règles sur les lignes de champ données dans [Champs magnétiques et lignes de champ magnétique] sont nécessaires pour plus de détails. Il existe une formule simple pour l'intensité du champ magnétique au centre d'une boucle circulaire. C’est vrai

$B = \frac{\mu_{0}I}{2R}\ (\text{au centre de la boucle})\text{,}$

22.26

où $R$ est le rayon de la boucle. Cette équation est très similaire à celle d'un fil droit, mais elle n'est valable *qu'au centre d'une boucle circulaire de fil. La similitude des équations indique que l'intensité du champ peut être obtenue au centre d'une boucle. Une façon d'obtenir un champ plus grand est d'avoir des boucles de $N$ ; alors, le champ est $B = {N\mu}_{0}I/(2R)$. Notez que plus la boucle est grande, plus le champ en son centre est petit, car le courant est plus éloigné.

! [][2]

Figure 22.38 (a) RHR-2 donne la direction du champ magnétique à l'intérieur et à l'extérieur d'une boucle porteuse de courant. (b) Une cartographie plus détaillée à l'aide d'une boussole ou d'une sonde à effet Hall complète le tableau. Le champ est similaire à celui d'un barreau magnétique.

## Champ magnétique produit par un solénoïde porteur de courant

Un solénoïde est une longue bobine de fil (avec de nombreux tours ou boucles, par opposition à une boucle plate). En raison de sa forme, le champ à l'intérieur d'un solénoïde peut être très uniforme et aussi très fort. Le champ juste à l'extérieur des bobines est presque nul. [Figure 22.39] montre à quoi ressemble le champ et comment sa direction est donnée par RHR-2.

! [][3]

Figure 22.39 (a) En raison de sa forme, le champ à l'intérieur d'un solénoïde de longueur $l$ est remarquablement uniforme en amplitude et en direction, comme l'indiquent les lignes de champ droites et uniformément espacées. Le champ à l'extérieur des bobines est presque nul. (b) Cette coupe montre le champ magnétique généré par le courant dans le solénoïde.

Le champ magnétique à l'intérieur d'un solénoïde porteur de courant est très uniforme en direction et en amplitude. Ce n'est que vers les extrémités qu'il commence à s'affaiblir et à changer de direction. Le champ extérieur a des complexités similaires à celles des boucles plates et des barres magnétiques, mais l'intensité du champ magnétique à l'intérieur d'un solénoïde est simplement

$B = \mu_{0}\text{nI}\ \ (\text{à l'intérieur d'un solénoïde}),$

22.27

où $n$ est le nombre de boucles par unité de longueur du solénoïde $(n = N/l$, $N$ étant le nombre de boucles et $l$ la longueur). Notez que $B$ est l'intensité du champ n'importe où dans la région uniforme de l'intérieur et pas seulement au centre. De grands champs uniformes répartis sur un grand volume sont possibles avec des solénoïdes, comme [Exemple 22.7] l'implique.

## Exemple 22.7 {#example-22.7 . Titre3Gris}

### Calcul de l'intensité du champ à l'intérieur d'un solénoïde {#calculating-intensité-de-champ-à-l'intérieur d'un-solénoïde . Titre4Gris}

Quel est le champ à l'intérieur d'un solénoïde de 2,00 m de long qui a 2000 boucles et transporte un courant de 1600 A ?

### Stratégie {#strategy-1 . Titre4Gris}

Pour trouver l'intensité du champ à l'intérieur d'un solénoïde, nous utilisons $B = \mu_{0}\text{nI}$. Tout d'abord, nous notons que le nombre de boucles par unité de longueur est

$n = \frac{N}{l} = \frac{\text{2000}}{2.00\ m} = \text{1000}\ \text{m}^{- 1} = \text{10}\ \text{cm}^{- 1}\text{.} $

22.28

### Solution {#solution-1 . Titre4Gris}

La substitution de valeurs connues donne

! [équation multiligne, ligne 1, majuscule B, égale mu sous-zéro fois nI, égale parenthèse gauche, quatre pi fois 10, super négative, sept fois cap, T, point postfixe, m barre oblique, majuscule A, parenthèse droite multipliée par la parenthèse gauche, 1000 m, super négative, une parenthèse droite fois parenthèse gauche 1600, capuchon A, parenthèse droite, ligne 2, blanc, égal à deux 0,01, majuscule, point T]

22.29

### Discussion {#discussion-1 . Titre4Gris}

Il s'agit d'une grande intensité de champ qui pourrait être établie sur un solénoïde de grand diamètre, comme dans les utilisations médicales de l'imagerie par résonance magnétique (IRM). Le très grand courant est cependant une indication que les champs de cette intensité ne sont pas faciles à atteindre. Un courant aussi important à travers 1000 boucles comprimées dans une longueur d'un mètre produirait un chauffage important. Des courants plus élevés peuvent être obtenus en utilisant des fils supraconducteurs, bien que cela soit coûteux. Il y a une limite supérieure au courant, car l'état supraconducteur est perturbé par de très grands champs magnétiques.

Il existe des variantes intéressantes de la bobine plate et du solénoïde. Par exemple, la bobine toroïdale utilisée pour confiner les particules réactives dans les tokamaks ressemble beaucoup à un solénoïde plié en cercle. Le champ à l'intérieur d'un tore est très fort mais circulaire. Les particules chargées se déplacent en cercles, suivant les lignes de champ, et entrent en collision les unes avec les autres, induisant peut-être une fusion. Mais les particules chargées ne traversent pas les lignes de champ et ne s'échappent pas du toroïde. Toute une gamme de formes de bobines est utilisée pour produire toutes sortes de formes de champ magnétique. L'ajout de matériaux ferromagnétiques produit des intensités de champ plus importantes et peut avoir un effet significatif sur la forme du champ. Les matériaux ferromagnétiques ont tendance à piéger les champs magnétiques (les lignes de champ se courbent dans le matériau ferromagnétique, laissant des champs plus faibles à l'extérieur) et sont utilisés comme boucliers pour les appareils qui sont affectés négativement par les champs magnétiques, y compris le champ magnétique terrestre.

## PhET Explorations {#phet-explorations . Titre3Gris}

### Générateur {#generator . Titre4Gris}

Produisez de l'électricité à l'aide d'une barre magnétique ! Découvrez la physique derrière les phénomènes en explorant les aimants et comment vous pouvez les utiliser pour fabriquer une ampoule.

[Cliquez pour voir le contenu].

  [Figure 22.37] : #import-auto-id1166991852141
  [1] : media/rId23.jpeg {width="2.60416666666666665in » height="4.3736636045494315in"}
  [équation multiligne, ligne 1, majuscule I égale deux fois pi rB divisé par mu, indice nul, égal à deux fois pi fois parenthèse gauche, 5,0 fois 10, super négatif, deux fois m, parenthèse droite multipliée par parenthèse gauche, 1,0 fois 10, super négatif, quatre fois capuchon, T, parenthèse droite divisée par quatre fois pi fois 10, super négatif sept fois cap, T postfix, point, m barre oblique, majuscule A, ligne 2, blanc égal à 25, majuscule A, point] :  media/rId28.png {width="2.552083333333333335in » height="0.52083333333333334in"}
  [Champs magnétiques et lignes de champ magnétique] : http://openstax.org/books/college-physics-2e/pages/22-3-magnetic-fields-and-magnetic-field-lines
  [Figure 22.38] : #import-auto-id1166991829247
  [2] : media/rId43.jpeg {width="4.6875in » height="2.6343744531933506in"}
  [Figure 22.39] : #import-auto-id1166991829619
  [3] : media/rId48.jpeg {width="5.7291666666666667in » height="2.744270559930009in"}
  [Exemple 22.7] : #fs-id2566108
  [équation multiligne ligne ligne 1 cap B égal mu indice zéro fois nI égal parenthèse gauche quatre pi fois 10 super négatif sept fois cap T postfixe point m barre oblique cap Une parenthèse droite multipliée parenthèse gauche 1000 m super négative une parenthèse droite fois parenthèse gauche 1600 cap A parenthèse droite ligne 2 Blanc égal à deux 0,01 cap T point] :  media/rId53.png {width="3.802083333333333335in » height="0.4270833333333333in"}
  [Cliquez pour voir le contenu] : https://openstax.org/l/28gen
