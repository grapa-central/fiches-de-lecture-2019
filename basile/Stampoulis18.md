## Références

* Prototyping a Functional Language using Higher-Order Logic Programming: A Functional Pearl on Learning the Ways of λProlog/Makam
* Antonis Stampoulis (Originate Inc.), Adam Chlipala (MIT CSAIL)
* International Conference on Functional Programming, 2018

## Résumé

L'article se présente comme un tutoriel, destiné à présenter les spécificités du langage λProlog, ou plus exactement de son dialecte Makam, principalement destiné à être utilisé comme meta-langage. Le tutoriel présente donc l'implémentation d'un prototype de vérificateur de types pour un langage "à la ML".

Pour ce faire, le tutoriel commence par présenter l'encodage d'un classique λ-calcul simplement typé, en montrant comment les fonctionnalités de λProlog permettent de se passer d'un contexte de typage explicite. Une construction permettant des bindings multiples est ensuite introduite.

L'article décrit ensuite le polymorphisme Ad-Hoc offert par Makam, permettant d'encoder des GADT, ainsi que des types dépendants tels que "La Liste Qui Connaît Sa Longueur" et "Le Binding Qui Connait Sa Longueur". Ce dernier type permet une représentation simple de pattern matching. Ce dernier type permet une représentation simple de pattern matching. Ce dernier type permet une représentation simple de pattern matching. Ce dernier type permet une représentation simple de pattern matching.

On présente ensuite la récursion structurelle, une fonctionnalité de Makam permettant d'éviter de redéfinir tous les case répétitifs d'un prédicat. Cette fonctionnalité est utilisée pour compléter l'implémentation d'un système de type complet avec polymorphisme, ADTs, définitions mutuellement récursives. De plus, le langage représenté est également équipé lui-même de fonctionnalités de métalangage, lui permettant de manipuler des objets d'un langage STLC. L'ensemble de ces fonctionnalités, et la simplicité de leur composition démontre de l'utilité de Makam en tant que métalangage.

## Contexte scientifique

L'article s'appuie sur les travaux de [Milner78](https://www.sciencedirect.com/science/article/pii/0022000078900144) sur le polymorphisme, mais surtout sur les travaux portant sur λProlog ([Nadathur88](https://repository.upenn.edu/cgi/viewcontent.cgi?article=1627&context=cis_reports), [Nadathur99](https://www-users.cs.umn.edu/~ngopalan/papers/teyjus.pdf) à propos de Teyjus). Le tutoriel fait aussi évidemment référence à [l'implémentation de Makam](https://github.com/astampoulis/makam).

## Pertinence

Cet article est particulièrement pédagogique, en particulier grace à sa présentation sous forme de dialogue progressant des concepts simples vers des constructions plus complexes et spécialisées de Makam. Malheureusement, il se trouve que cet article n'est malgré tout que peut utile à notre travail : en effet il ne couvre aucun des détails d'implémentation de l'interpréteur de Makam utilisé. De plus, le tutoriel se concentre également sur certaines fonctionalités spécifiques au dialecte, que nous n'implanterons probablement pas dans la première version de notre travail.

On pourra cependant se référer à l'article pour trouver des bons exemples de tests pour notre interpréteur, en particulier en ce qui concerne l'encodage de types dépendants / GADT.
