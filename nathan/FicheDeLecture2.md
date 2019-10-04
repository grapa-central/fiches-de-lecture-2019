*Nathan GERDAY*

# Références

**Titre :** Explicit Substitutions in the Reduction of Lambda Terms

**Auteurs :** Gopalan Nadathur, Xiaochu Qi

**Conference :** ACM SIGPLAN Conference on Principles and Practice of Declarative Programming, 2003

# Résumé

L'objectif de cet article est de résoudre le problème de la substitution de lambda termes qui peut être très couteuse, notamment en terme d'espace dans la pile. Pour palier à ce problème l'article propose 3 principales procédures et les présentent via une implémentation dans le langage SML. La 3ème étant supposément la plus optimale, étant donné qu'elle reprend des éléments intéressants des 2 premières. L'article présente également des ensembles de règles formelles utilisés dans la méthode de calcul de substitution appelé "Notation de Suspension" qui est utilisée au travers des différentes approches proposées.


# Contexte Scientifique

Ce papier cite d'autres articles intéressants tels que [An efficient interpreter for the lambda-calculus.](https://www.sciencedirect.com/science/article/pii/0022000081900738) par L. Aiello et G. Prini, qui bien qu'il n'est pas lié directement à lambda prolog, peut donner des idées intéressantes par rapport a l'évaluation de lambda calcul. Il s'appuie également sur plusieurs autres travaux de G. Nadathur et D. Miller qui sont souvent liés à des sujets intéressants par rapport à notre projet.   
Ce papier est cité dans peu d'autres articles qui ne semblent pas particulièrement intéressants pour nous. Pour en citer un, nous pouvons tout de même donner [A treatment of higher-order features in logic programming](https://arxiv.org/pdf/cs/0404020.pdf)

# Pertinence

Bien que cet article ne pourra pas nous aider sur la structure générale de l'interpréteur étant donné qu'il se concentre uniquement sur la résolution des substitutions, lorsqu'on nous arriverons au moment où nous devons les implémenter, il pourra nous être d'une grande aide. En effet, en plus d'être assez explicite et détaillé dans toutes les règles et procédures qu'ils utilisent, il y a également des exemples déjà écrit dans le langage SML qui nous simplifieront grandement la tâche pour les reprendre et les adapter dans notre projet.

**Avis : Bonne pertinence**