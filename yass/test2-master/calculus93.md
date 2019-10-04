# A calculus for the random generation of labelled combinatorial structures 

# Référence
Auteur : Philippe Flajolet, Paul Zimmerman, Bernard Van Custem
Revue : Theorical Computer Science 132 (1994)

# Résumer 
C'est un article sur la généralisation des techniques de générations aléatoires existant dans la littérature sur les arbres et dans le domaine du langage et de la grammaire.
<br>Le papier présente d'abord et définis les différentes structures décomposables qui seront étudier dans l'article et leur spécification. Puis il montre comment généraliser leur spécification en spécification dite *standard*.
<br>Les auteurs montrent ensuite deux techniques de générations aléatoires,qui nécessitent un precalcul en O(n&sup2;),  l'algorithme séquentiel en O(n&sup2;) en pire cas qui présente des améliorations possible en cas moyen en (1/2 nlogn) qui se base sur le parcours de la spécification et l'utilisation de routine et l'algorithme boustrophedonic étend une idée de Knuth qui se base sur les permutations. L'article contient aussi une méthode de calcul de complexité en moyenne.
# Contexte Scientifique
Cet article repose beaucoup sur les travaux de Nijenhuis et Wilf dans leur livre *Combinatorial Algorithms (Academic Press, New York, 2nd édition, 1978)* de T. Hickey and J. Cohen,*Uniform random generation of strings in a context-free language, SIAM J.Comput. 12(4) (1983) 645-655.* ,D.H. Greene, *Labelled formal languages and their uses, Ph.D. thesis, Stanford University, June 1983;
available as Report No. STAN-CS-83-982.* et *N.G. De Bruijn, Asymptotic Methods in Analysis (Dover, New York, 1981).* pour la partie algorithme séquentiel et sur D.E. Knuth, *Mathematical analysis of algorithms, in: Information Processing 71 (North-Holland,
Amsterdam, 1972) 19-27.* pour l'algorithme boustrophedonic.
<br>Zimmerman a continué ses recherche, en effet dans l'article il parle d'optimisation en utilisant les flotants ce qu'il utilisera pour écrire un autre papier A. Denise, P. Zimmermann *Uniform random generation of decomposable structures using floating-point arithmetics
Theoret. Comput. Sci., 218 (1999), pp. 233-248*
<br>Cet article semble avoir eu un impact important il a été cité de nombreuses fois.
# Pertinence 
Cet article semble avoir un impact important dans le domaine,en effet malgré que Zimmerman ait écrit un article sur une optimisation de l'algorithme,ce papier semble contenir beaucoup d'information de base qui pourrait etre utile pour comprendre l'article qu'il a écrit ensuite.
