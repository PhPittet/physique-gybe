# L'effet Hall
Nous avons vu les effets d'un champ magnétique sur les charges en mouvement libre. Le champ magnétique affecte également les charges se déplaçant dans un conducteur. L'un des résultats est l'effet Hall, qui a des implications et des applications importantes.

La figure 22.26 montre ce qu'il advient des charges se déplaçant à travers un conducteur dans un champ magnétique. Le champ est perpendiculaire à la vitesse de dérive de l'électron et à la largeur du conducteur. Notez que le courant conventionnel est à droite dans les deux parties de la figure. Dans la partie (a), les électrons transportent le courant et se déplacent vers la gauche. Dans la partie (b), les charges positives transportent le courant et se déplacent vers la droite. Les électrons en mouvement ressentent une force magnétique vers un côté du conducteur, laissant une charge positive nette de l'autre côté. Cette séparation de charge *crée une tension*, $\epsilon$ connue sous le nom de `force électromotrice de Hall`, aux bornes du conducteur. La création d'une tension aux bornes d'un  conducteur porteur de courant par un champ magnétique est connue sous le nom d'effet Hall, d'après [Edwin Hall](https://fr.wikipedia.org/wiki/Edwin_Herbert_Hall), le physicien américain qui l'a découvert en 1879.
 
**Figure 22.26 L'effet Hall. (a) Les électrons se déplacent vers la gauche dans ce conducteur plat (courant conventionnel vers la droite). Le champ magnétique est directement à l'extérieur de la page, représenté par des points encerclés ; il exerce une force sur les charges en mouvement, provoquant une tension, la force électromotrice de Hall, à travers le conducteur. (b) Les charges positives se déplaçant vers la droite (courant conventionnel également vers la droite) sont déplacées sur le côté, produisant une force électromotrice de Hall de signe opposé, . Ainsi, si la direction du champ et le courant sont connus, le signe des porteurs de charge peut être déterminé à partir de l'effet Hall.**

Une utilisation très importante de l'effet Hall est de déterminer si des charges positives ou négatives transportent le courant. Notez que dans  la Figure 22.26 (b), où les charges positives transportent le courant, la force électromotrice de Hall a le signe opposé à celui des charges négatives qui transportent le courant. Historiquement, l'effet Hall a été utilisé pour montrer que les électrons transportent le courant dans les métaux et il montre également que les charges positives transportent le courant dans certains semi-conducteurs. L'effet Hall est aujourd'hui utilisé comme outil de recherche pour sonder le mouvement des charges, leurs vitesses de dérive et leurs densités, etc., dans les matériaux. En 1980, il a été découvert que l'effet Hall est quantifié, un exemple de comportement quantique dans un objet macroscopique.

L'effet Hall a d'autres utilisations qui vont de la détermination du débit sanguin à la mesure précise de l'intensité du champ magnétique. Pour les examiner quantitativement, nous avons besoin d'une expression pour la force électromotrice de Hall, , aux bornes d'un conducteur. Considérons l'équilibre des forces sur une charge en mouvement dans une situation où $B$, $v$ et $l$ sont mutuellement perpendiculaires, comme le montre la Figure 22.27. Bien que la force magnétique déplace les charges négatives d'un côté, elles ne peuvent pas s'accumuler sans limite. Le champ électrique causé par leur séparation s'oppose à la force magnétique, $F=qvB$, et la force électrique, $F_{e}=qE$, finit par croître pour s'égaler. Ce qui donne :
:::{math}
qE=qvB\\
E=VB
:::
Notez que le champ électrique $E$ est uniforme à travers le conducteur car le champ magnétique est uniforme, tout comme le conducteur. Pour un champ électrique uniforme, la relation entre le champ électrique et la tension est $E=\frac{\epsilon}{l}$, où $l$ est la largeur du conducteur et $\epsilon$ est la force électromotrice de Hall. En entrant ceci dans la dernière expression, on obtient :
:::{math}
\dfrac{\epsilon}{l}=vB
:::
La résolution de ce problème pour la force électromotrice de Hall donne :
:::{math}
\epsilon=Blv
:::
où est $\epsilon$ la tension à effet Hall aux bornes d'un conducteur de largeur $l$ à travers lequel les charges se déplacent à une vitesse $v$.
 
**Figure 22.27 La force électromotrice de Hall produit une force électrique qui équilibre la force magnétique sur les charges en mouvement. La force magnétique produit une séparation de charge, qui s'accumule jusqu'à ce qu'elle soit équilibrée par la force électrique, un équilibre qui est rapidement atteint.**

L'une des utilisations les plus courantes de l'effet Hall est la mesure de l'intensité du champ magnétique. De tels dispositifs, appelés sondes à effet Hall, peuvent être très petits, ce qui permet une cartographie fine de la position. Les sondes à effet Hall peuvent également être rendues très précises, généralement grâce à un étalonnage minutieux. Une autre application de l'effet Hall est de mesurer l'écoulement d'un fluide dans n'importe quel fluide qui a des charges libres (la plupart le font). (Voir Graphique 22.28.) Un champ magnétique appliqué perpendiculairement à la direction d'écoulement produit une force électromotrice de Hall $\epsilon$ comme indiqué. Notez que le signe de $\epsilon$ ne dépend pas du signe des charges, mais uniquement des directions de $B$ et $v$. L'amplitude de la force électromotrice de Hall est $\epsilon=Blv$, où $l$ est le diamètre du tuyau, de sorte que la vitesse moyenne $v$ peut être déterminée à condition que les autres facteurs soient connus.
 
**Figure 22.28 L'effet Hall peut être utilisé pour mesurer l'écoulement d'un fluide dans n'importe quel fluide ayant des charges libres, comme le sang. La force électromotrice de Hall $\epsilon$ est mesurée à travers le tube perpendiculairement au champ magnétique appliqué et est proportionnelle à la vitesse moyenne $v$.**

:::::{admonition} Exemple : Calcul de la force électromotrice de Hall
:class: exores
Calcul de la force électromotrice de Hall : effet Hall pour le flux sanguin.\\
Une sonde de débit à effet Hall est placée sur une artère, en appliquant un champ magnétique de $0.100\,T$ à travers celle-ci, dans une configuration similaire à celle de la figure 22.28. Qu'est-ce que la force électromotrice de Hall, étant donné que le diamètre intérieur du vaisseau est de $4.00\,mm$ et que la vitesse moyenne du sang est de $20.0\,cm/s$ ?
::::{admonition} *stratégie*
:class: dropdown strategie
Comme $B$, $l$ et $v$ sont mutuellement perpendiculaires, l'équation $\epsilon=Blv$ peut être utilisée pour trouver $\epsilon$.
::::
::::{admonition} *solution*
:class: dropdown solution
La saisie des valeurs données pour $B$, $l$ et $v$ donne :
:::{math}
\epsilon=Blv=(0.1\,T)\cdot (4.00\cdot 10^{-3}\,m)\cdot (0.200\,m/s)=80.0\cdot 10^{-6}\,V=80\,\mu V
:::
::::
::::{admonition} *discussion*
:class: dropdown discussion
Il s'agit de la tension de sortie moyenne. La tension instantanée varie en fonction du flux sanguin pulsé. La tension est faible dans ce type de mesure. $\epsilon$ est particulièrement difficile à mesurer, car il existe des tensions associées à l'action cardiaque (tensions ECG) de l'ordre du millivolt. Dans la pratique, cette difficulté est surmontée par l'application d'un champ magnétique alternatif, de sorte que la force électromotrice de Hall soit AC avec la même fréquence. Un amplificateur peut être très sélectif en ne choisissant que la fréquence appropriée, éliminant ainsi les signaux et le bruit à d'autres fréquences.ε
::::
:::::
