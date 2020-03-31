---
layout: post
title: Expliquer Internet à un enfant
date: 2020-03-31 17:20:00 -0100
categories: fr internet
---

Je travaille sur un projet de présentation, ayant pour thème "Internet et vie privée", que j'aimerais faire dans des lycées afin de sensibiliser à l'utilisation du web et à ce qu'il arrive à nos données lors de leur voyage dans le monde magique d'Internet.

Mais avant d'aborder ce sujet, des bases sur le pourquoi du comment de ce monde magique s'imposent. Je me suis donc posé la question : comment expliquer Internet à des gens qui ne connaissent sûrement pas grand chose à son fonctionnement, ou pour généraliser : comment expliquer Internet à un enfant ? Ça me permet également de me poser des questions sur mes connaissances, car 
> Ce que l'on conçoit bien s’énonce clairement. (Nicolas Boileau)

Alors voici mon premier chapitre, dédié à Internet :

## Inter-quoi ?

Internet, pour *interconnected networks*, n'est pas le world wide web. Le web est le service qui permet d'accéder grâce à un navigateur à du contenu. Ce contenu, lui, est amené à l'utilisateur en passant par Internet.

On retrouve donc les mots *interconnected* et *networks*. Pour les moins anglophones, la traduction littérale est *réseaux interconnectés*. Chouette, mais des réseaux de quoi ? Et interconnectés comment ?

## Des réseaux et des machines

Un réseau est un ensemble de relations. Ce terme peut s'appliquer aussi bien à un réseau professionnel par exemple, qu'à un réseau informatique. Pour ce dernier, les éléments qui le composent sont des équipements qui s'échangent des informations. Ces équipements peuvent être de natures diverses et variées : serveurs, ordinateurs, smartphones, switch et routeurs...

On remarque que *networks* est au pluriel : en effet, Internet est composé d'une multitude de réseaux, partout à travers le monde. 

## Connecter le monde

Différents supports sont utilisés pour connecter les machines entre elles : wi-fi, ethernet, câble coaxial, fibre... Chaque support à ses spécificités, mais lorsque les distances sont très longues (par exemple pour traverser un océan) c'est la fibre qui est utilisée. Vous pouvez retrouver une carte du déploiment mondial de fibre [ici](https://www.submarinecablemap.com/), ainsi qu'un bon article sur le sujet [ici](http://webdoc.rfi.fr/ocean-cables-sous-marins-internet/chapitre-1.html).

Ce sont grâce à ces supports que les données transitent des serveurs jusqu'à votre ordinateur. Mais comment ?

## Les paquets

Pour faire simple, lorsque l'on cherche à accéder à un serveur, on lui fait une requête contenant ce que l'on veut avoir (page, images, vidéos, posts...).
Le serveur en question nous répond donc avec le contenu demandé, emballé dans ce que l'on appelle des paquets.

À chaque demande, il y en a une flopée. Un fois que notre ordinateur reçoit ces paquets, il les ouvre et les assemble, ce qui restitue le contenu auquel nous voulons accéder. Ces paquets parcourent donc une multitude de réseaux entre le serveur et nous. Il est important de comprendre qu'il n'existe pas de lien __direct__ entre un serveur et notre ordinateur. Pour accéder à un serveur, vous devez passer par un certain nombre de réseaux, qui potentiellement voient votre requête et sa réponse.

## Conclusion

Je dirai que ce qu'il est important de retenir, c'est que la navigation est un échange constant d'informations passant par Internet, c'est à dire transitant par de nombreux réseaux. Comme nous n'avons pas le contrôle sur tous ces réseaux, il parait important de s'assurer que ces données qui transitent soient chiffrées, c'est à dire impossible à lire par qui n'est pas autorisé, mais nous verrons ça dans une prochaine partie !