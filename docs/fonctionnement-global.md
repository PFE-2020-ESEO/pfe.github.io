---
layout: doc
title: Fonctionnement Global
description: Voici une courte explication du fonctionnement de notre système.
toc: true
---

### Explication non technique

Actics est une bibliothèque do'outils qui ont été développé par les membres d'Actics ou les utilisateurs développeurs. Ces outils sont hébergé sur les serveurs sécurisés de Actics. 

Notre base de donnée rassemble chacun de ces outils et les paramètres nécessaire pour les faire fonctionner. Ainsi lorsque vous accédez a notre plateforme et que vous choisissez un outil en remplissant les paramètres nécessaire, notre système va lancer le code avec vos paramètre sur une partie spécifique de notre serveur. Cela permet de lancer votre outil en toute sécurité et lui permet de fonctionner en autonomie rien que pour vous. 

Lorsque vous décidez d'arrêter votre outil nous allons éteindre cette partie spécifique du serveur qui vous avait été attribué et nous l'utilisons pour un autre outil d'un autre utilisateur. 

Notre serveur a été conçu ainsi pour faire fonctionner des centaines d'outils en même temps ! Alors lancez vous !

-------------------------------

### Explication technique

L'explication technique sera étoffé plus tard voici un schéma technique pour avoir un apperçu.

{% include image.html url="/images/doc/system.png" description="fonctionnement" width="700"%}
