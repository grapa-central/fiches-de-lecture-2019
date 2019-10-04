## Référence

- [Gaspard Huet](http://gallium.inria.fr/~huet/index.html)
- "A unification algorithm for typed λ-calculus"
- Th. Computer Science 1 (1975)

## Résumé

L'auteur présente le λ-calcul typé simplement -- pour lequel la réduction
termine toujours -- et un algorithme d'unification des λ-termes simplement
typés sous forme normale. En logique du premier ordre, deux termes unifiables
ont un "Most General Unifier" bien connu. De tels unificateurs n'existent pas
pour le λ-calcul, du à la présence de variables fonctionnelles (d'ordre
supérieur). Ce problème est indécidable dans le cas général en présence de
variables d'ordres supérieure. L'algorithme présenté termine avec un unificateur
s'il existe, mais peut ne pas terminer si les termes ne sont pas unifiables.

L'article ouvre sur une présentation du λ-calcul simplement typé, puis décrit un
algorithme d'unification non-déterministe, prouve sa correction et complétude
(si un unificateur existe). L'unification procède par exploration d'un arbre
dont les noeuds sont des paires de termes à unifier, et les liens sont des
substitutions élémentaires. Enfin, il est exposé des améliorations heuristiques
sur cet algorithme.

## Contexte scientifique

L'article date d'il y a 45 ans. Il se base sur les travaux précédents de
l'auteur dans le même domaine (indécidabilité du problème d'unification pour le
3eme ordre, nécessite des recherches redondantes de substitution pour le MGU).
la thèse de Huet portait sur la résolution d'équations dans les langages
d'ordre quelconque. 

Les travaux de Huet se poursuivront dans le domaine de la loqique formelle et
de l'informatique théorique. Il participera à la création de Coq, qui utilise un
système de réécriture pour prouver mécaniquement l'égalité de valeurs d'ordre
supérieur. On y retrouve des considérations similaires concernant le typage et
l'unification (au sens large) des termes d'un langage.

## Pertinence

Dans l'optique de comprendre et d'implémenter un interpréteur λProlog, il est
utile de comprendre les algorithmes d'unification à notre portée. Néanmoins,
l'age de l'article est un problème. D'autres solutions du problème de
l'unification ont été données en se basant sur les travaux de Huet et les
progrès en programmation loqique. On retiendra cet article pour son intérêt
culturel et son introduction au problème de l'unification des λ-termes sans
prérequis autre que la connaissance du λ-calcul simplement typé. 
