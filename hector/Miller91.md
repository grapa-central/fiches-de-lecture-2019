## Références

- [Dale Miller](https://www.lix.polytechnique.fr/Labo/Dale.Miller/)
- Unification of Simply Typed Lambda-Terms as Logic Programming
- Rapport de recherche pour de dpt. d'informatique de UPenn

## Résumé

L'article présente une réduction du problème d'unification des λ-termes d'ordre
supérieur simplement typés sous β-η-réduction, en l'implémentant dans un
langage de programmation logique du premier ordre Lλ. L'unification est d'abord
présentée comme une requète dans le formalisme des formules de Harrop
héréditaires (hhω), dans lequel il a une traduction claire. hhω est en fait un
interpréteur de programmation logique, qui doit effectuer des β-réduction
arbitraire pour unifier les λ-terms.

L'auteur introduit ensuite le langage Lλ, qui est une restriction de hhω aux
buts et programmes "essentiellement quantifiés". Il montre que dans cette
restriction, l'unification ne nécessite de faire que des β-réductions qui
conservent la morphologie des λ-termes, nommées β0-réductions. L'unification des
termes d'ordre supérieurs dans Lλ modulo β0-η-réduction est décidable, et les
unificateurs les plus généraux (MGU) existent bien dans Lλ.

L'article présente une spécification de l'égalité des λ-termes sous
β-η-réduction et de la substitution dans Lλ, et une réduction des buts de hhω
dans ceux de Lλ (le cas des programmes étant simple). Avec cette réduction, il
est prouvé que le problème de l'unification des λ-termes d'ordre supérieur
modulo β-η-réduction se ramène à celui de l'interprétation d'une requète dans
Lλ. Finalement, l'auteur donne des indication concernant l'implémentation
potentielle de Lλ.

## Contexte scientifique

L'article se différencie des recherche précédente sur le sujet en ne donnant pas
un algorithme spécifique pour l'unification. En se basant sur les travaux
précédents sur le sujet et les implémentations de langages fonctionnels logiques,
notamment λProlog à laquelle Miller a participé, l'auteur donne une nouvelle
perspective du problème. 

## Pertinence

L'auteur remarque bien que de nombreux détails essentiels d'implémentation de
l'unification sont passés sous le tapis: l'auteur suppose l'existence d'un
interpréteur non-deterministe de Lλ dont l'implémentation n'est pas triviale.
Mais les difficultés d'une telle implémentation sont connues, et l'ont peut
implémenter à partir d'autre langages de programmation logique. Comme l'auteur
le remarque, Lλ peut être une partie pertinente de l'implémentation de λProlog. 
