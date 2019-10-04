*Nathan GERDAY*

# Références

**Titre :** ELPI: fast, Embeddable, λProlog Interpreter

**Auteurs :** Cvetan Dunchev, Ferruccio Guidi, Claudio Sacerdoti Coen, Enrico Tassi

**Conference :** International Conference on Logic for Programming Artificial Intelligence and Reasoning, Novembre 2015

# Résumé

L'article présente l'interpréteur Lambda-Prolog ELPI en se concentrant notamment sur sa rapidité grâce à l'identification de certaines parties du langages qu'ils appellent "reduction-free fragment" et qui peuvent se réduire et s'unifier en temps constant.  
Ils expliquent tout d'abord les rôles de la beta reduction en Lambda Prolog et explique le fonctionnement dans l'interpreteur en l'illustrant avec un exemple.   
Ils parlent également de comment résoudre les problèmes d'unifications d'ordre supérieur sans énumérer l'ensemble des solutions une à une ou comment représenter les variables liés.  
Il est également intéressant de noter qu'en plus d'expliquer certaines approches utilisées dans l'interpréteur ELPI, ils les comparent également à celles de Teyjus pour certains problèmes.

# Contexte Scientifique

Ce papier cite d'autres articles intéressants tels que [A Logic Programming Language with Lambda-Abstraction,Function Variables, and Simple Unification](https://pdfs.semanticscholar.org/8935/8a00317f9e380abe02b9f0d04536a6cd3121.pdf) par L. Aiello et G. Print  ou encore, Teyjus - A compiler and abstract machine basedimplementation ofλprolog, par G. Nadathur and D. J. Mitchell.  
Il est cité dans d'autres articles tel que [Prototyping a functional language using higher-order logic programming: a functional pearl on learning the ways of λProlog/Makam](https://dl.acm.org/citation.cfm?id=3236788) par A. Stampoulis et A. Chipala


# Pertinence

Cet article, bien que très spécifique à la résolution de certains problèmes donnés et orienté vers le fait de créer un interpreteur très efficace pour certains cas précis, semble intéressant sur certains points grâce au fait qu'il explique le fonctionnement et les approches utilisées à la fois par ELPI et Teyjus. Nous ne pourrons pas obtenir de moyens détaillés de procéder a l'implémentation dans cette article mais nous pouvons tout de même obtenir des pistes et idées intéressantes.  
Il ne faut cependant pas oublier que l'article a été réalisé dans le but de montrer les qualités de ELPI et qu'il est donc très orienté.

**Avis : Pertinence moyenne**