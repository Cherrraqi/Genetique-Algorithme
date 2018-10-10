
---
title: 'Genetique-Algorithme'
date: 2012-08-14
permalink: /posts/2012/08/blog-post-1/
tags:
  - cool posts
  - category1
  - category2
---



Recherche de l’optimum global d’une fonction multimodale

Pseudo Code :

t=0;

initialiser p(0)

evaluer p(0)
 repeter 
   {t++;
   selectionner les parents 
   creer une nouvelle population p(t);
   evaluer p(t)
   } jusqu a candition d arrret 
 

g++ main.cpp genetique.cpp -o  exec
./exec
