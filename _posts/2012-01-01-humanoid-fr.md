---
title: Command d'un robot humanoïde
lang: fr
content_type: project
---

![Tidom]({{ "assets/images/tidom-large.jpg" | relative_url }})

Quel projet intéressant! Avant de commencer mon doctorat, j'ai travaillé comme chercheur en France. Le projet consistait à travailler sur la locomotion d'un robot humanoïde (pas The Terminator). Ce robot (Tidom) avec un total de 12 articulations dans ses deux jambes a environ la taille d'un enfant de quatre ans.

Mon travail consistait à construire l'algorithme de contrôle à partir de zéro pour contrôler les 12 moteurs de manière synchrone afin de permettre à d'autres chercheurs de mettre en œuvre leurs expériences sur le robot. Pour ce faire, j'ai conçu un programme C sur un automate programmable (PLC) pour communiquer avec et commander tous les microcontrôleurs de chaque articulation en utilisant la communication CANopen. CANopen est une norme de communication basée sur CAN, et comme l'API que nous utilisions n'avait que des bibliothèques CAN, j'ai construit ma propre implémentation de CANopen pour pouvoir parler avec les contrôleurs des moteurs.

## Expertise développée
- Commande temps réel
- C/C++
- Programmation PLC
- CAN / CANopen
- Commande et réglage de moteur DC
