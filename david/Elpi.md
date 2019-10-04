# Références

* *Cvetan Dunchev, Ferruccio Guidi, Claudio Sacerdoti Coen, Enrico Tassi.* [ELPI: fast, Embeddable, λProlog Interpreter](https://hal.inria.fr/hal-01176856/document).
* Proceedings of LPAR, Nov 2015, Suva, Fiji. hal-01176856

# Résumé

Ce rapport traite de l'amélioration de la performance de λProlog avec leur interpreteur ELPI en se basant sur la détection de ce qu'ils appellent "reduction-free fragments" de λProlog qui permettraient d'avoir des unifications et des reduction en temps constant. Il commence par expliquer les motivations de ces travaux qui est d'implementer un "elaborator" pour un assistant de preuve (interactive theorem prover ou ITP) et s'ensuit ensuite de la manière de procéder afin d'identifier ces "reduction-free fragments". Il se conclut ensuite avec une comparaison avec Teyjus, une autre implémentation de λProlog qui est jugé comme le plus performant.

# Contexte scientifique

Ce rapport est inspiré de travaux comme [Hints in Unification](https://link.springer.com/chapter/10.1007/978-3-642-03359-9_8) (2009, Andrea Asperti) ou encore [A logic programming language with lambda-abstraction, function variables, and simple unification](https://academic.oup.com/logcom/article-abstract/1/4/497/1092890/) (2012, Dale Miller). Il a également été utilisé dans des travaux comme [Implementing HOL in an Higher Order Logic Programming Language](https://dl.acm.org/citation.cfm?id=2966272) (2016, même auteur) ou [Elpi: an extension language for Coq (Metaprogramming Coq in the Elpi λProlog dialect)](https://hal.inria.fr/hal-01637063/document) (2018, Enrico Tassi).

# Pertinence

Ce rapport n'est pas pertinent pour le projet. En effet, il n'explique comment implementer un interpreteur de λProlog, il présente simplement quelques points/idées qui ont permis d'avoir les performances que montrent leur interpréteur, ELPI. Il est possible qu'il y ait quelques idées à soutirer du rapport mais elles ne serviraient qu'après avoir fini le projet pour l'améliorer.