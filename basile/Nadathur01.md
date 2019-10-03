## Références

* The Metalanguage λProlog and Its Implementation
* Gopalan Nadathur (University of Minnesota)
* International Symposium on Functional and Logic Programming, 2001

## Résumé

L'article présente une vue générale du langage λProlog. La première partie décrit les cas d'applications du langage pour lesquels les ajouts faits à Prolog (abstractions fonctionnelles, quantificateurs universels, objectifs contenant des implications) jouent un rôle particulièrement important. Ceux ci se concentrent en particulier sur le rôle de λProlog en tant que métalangage, et donc s'intéresse à l'analyse et la manipulation d'arbres de syntaxe abstraits, avec pour exemple central la détection de fonctions récursives terminales.

L'article décrit ensuite les difficultés posées par ces ajouts, et explore des solutions techniques utilisées pour les résoudre efficacement. En particulier, il se penche sur la représentation de λ-termes (avec indices de de Bruijn), en se concentrant sur les algorithmes de β-réduction et d'unification d'ordre supérieure.
L'article décrit également une solution au problème de résolution d'objectifs contenant des quantificateurs universels, au moyen d'un système de contraintes d'univers permettant de correctement instancier les variables de l'objectif. Enfin, le cas des objectifs contenant une implication, qui permettent d'ajouter dynamiquement des règles de déduction au programme, est également discuté.
Enfin, l'article introduit le compilateur Teyjus, implémenté à partir de ces idées.

## Contexte scientifique

L'article s'inspire des travaux réalisés sur l'unification d'ordre supérieure ([Huet75](https://www.sciencedirect.com/science/article/pii/0304397575900110)), ainsi que de travaux précédents de l'auteur, ainsi que de D.Miller et P.Brisset sur λProlog ([Brisset92](https://core.ac.uk/download/pdf/48274184.pdf), [Nadathur98](https://www.researchgate.net/publication/2659222_An_Explicit_Substitution_Notation_in_a_lamdaProlog_Implementation), ...). De plus, le compilateur Teyjus réalisé peu auparavant a également fait l'objet de publications ([Nadathur99](https://www-users.cs.umn.edu/~ngopalan/papers/teyjus.pdf)).
L'auteur a continué ses travaux après la publication de cet article, avec en particulier le livre [Programming with Higher-Order Logic](https://sites.google.com/site/proghol/), qui utilise le langage (et son compilateur Teyjus) pour illustrer ses concepts liés à la logique et au λ-calcul. Les contributions de l'article sont également observées dans [Momigliano10](https://link.springer.com/chapter/10.1007%2F978-3-642-14309-0_12/).

## Pertinence

Notre objectif étant de parvenir à une réalisation d'un interpréteur de λProlog, la deuxième partie de cette article semble tout indiquée pour nous donner des idées d'implémentation efficace des points précis listés plus haut. La première partie en revanche, semble plus dispensable, puisqu'elle sert plus à "convaincre" le lecteur de l'intérêt du langage, que de détailler son fonctionnement.
