# Références

* *Pascal Brisset.* [Implémentation d’un langage de programmation logique d’ordre supérieur avec MALI](https://hal.inria.fr/inria-00075440/document).
* [Rapport de recherche] RR-1119, INRIA. 1989. inria-00075440

# Résumé

Le rapport de recherche commence par présenter λProlog et les raisons qui ont conduit à l'implémentation de leur compilateur de Z, un langage se basant sur λProlog mais plus restreint. Il explique ensuite le typage des λ-termes que manipule λProlog et comment fonctionne l'unification d'ordre supérieur en donnant l'algorithme des différents traitements. Il présente ensuite la machine abstraite MALI utilisée pour implémenter le compilateur et comment la manipuler. Enfin il explique l'implémentation du compilateur.

# Contexte scientifique


Ce rapport est basé sur des travaux comme [A unification algorithm for typed λ-calculus](https://www.sciencedirect.com/science/article/pii/0304397575900110) (1975, Huet) ou encore "MALI: A Memory with a Real-time Garbage Collector for Implementing Logic Programming Languages" (1986, Yves Bekkers, Bernard Canet, Olivier Ridoux, Lucien Ungaro). Il a également inspiré des travaux comme [A new data structure for implementing extensions to Prolog](https://link.springer.com/chapter/10.1007/BFb0024181) (1990, Serge Le Huitouze) ou [Prolog de A à Z... ou presque](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.93.359&rep=rep1&type=pdf) (1998, Olivier Ridoux)

# Pertinence

Ce rapport semble pertinent pour la réalisation d'un interpréteur de λProlog. L'explication du de l'unification d'ordre supérieur et son algorithme nous seront très utiles. Quant à l'implémentation du compilateur, on peut avoir un doute étant donnée qu'elle se base sur la machine MALI qui simplifie les opérations. Il y a néanmoins probablement quelques idées à tirer du compilateur.