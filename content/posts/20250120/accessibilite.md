---
title: "L'accessibilité dans le logiciel libre"
description: "Essayer d'améliorer l'accessibilité du logiciel libre pour le rendre utilisable au plus grand nombre"
date: 2025-01-20
tags: ["Accessibilité", "Logiciel libre", "Dolibarr"]
---
S'il y a bien un reproche qui revient régulièrement concernant le **logiciel libre**, c'est son interface utilisateur (UI) ainsi que l'expérience utilisateur (UX) qui en découle.
La raison est plutôt simple : la plupart des contributrices et contributeurs sont avant tout des personnes qui font du développement, et pas des personnes ayant une expertise en UI/UX. Et ça se ressent.

L'**accessibilité**, quant à elle, est un sujet de plus en plus visible et à juste titre. Ne pas penser accessibilité lorsqu'on conçoit un outil, c'est de fait exclure une partie des utilisatrices et utilisateurs. L'ajouter à une UI/UX plus que perfectible, et l'outil ne sera pas adopté.
C'est pour cette raison que je m'intéresse à ce sujet depuis quelques temps et que j'ai décidé à mon petit niveau de faire avancer les choses comme je le peux dans le logiciel libre. Je ne suis certes pas un expert, je n'ai pas toutes les compétences nécessaires, mais comme on me le répète souvent : _done is better than perfect_. Il vaut mieux en faire un peu, avancer, plutôt que d'attendre d'avoir atteint la perfection avant de mettre en place.

J'ai donc commencé, puisque c'est le seul que je connais suffisamment bien, par **Dolibarr**. J'ai donc vu ma première Pull Request acceptée la semaine dernière. Celle-ci concernait l'utilisation de la balise `<label></label>` pour les `<input>` sur une seule page d'administration, pour prendre la température et voir si ça pouvait intéresser la communauté. Je vais donc continuer en ce sens et, progressivement, essayer d'améliorer l'accessibilité de l'outil, et bien entendu de reproduire cela avec d'autres projets libres. Ce sera aussi l'occasion de faire une série de billets sur mes découvertes à ce sujet au fil du temps.
