# Simulation de Lenia

Ce dépôt contient une simulation de Lenia, un modèle de vie artificielle qui s'appuie sur le Jeu de la Vie de John Conway.

Lenia, développé par Bert Wang-Chak Chan, repousse les limites des automates cellulaires. Contrairement à la grille discrète de Conway où les cellules sont soit vivantes, soit mortes, Lenia opère sur une grille continue, permettant aux cellules d'avoir une gamme d'états entre 0 et 1. Cela se traduit par des transitions plus fluides et des motifs plus complexes et organiques.

## Concepts Clés

### État Cellulaire et Voisinage

Dans Lenia, l'état de chaque cellule est représenté par une valeur continue entre 0 et 1, offrant un ensemble plus riche de comportements possibles par rapport aux états binaires du Jeu de la Vie. Le voisinage d'une cellule, qui influence son état, peut être défini selon différentes méthodes, telles que les voisinages de Moore ou de von Neumann.

### Espace et Temps Continus

La simulation de Lenia se déroule dans un espace bidimensionnel continu, offrant une grande précision dans la représentation des positions des cellules. Chaque étape de temps implique la mise à jour des états de toutes les cellules en fonction de leurs états actuels et de ceux de leurs voisines, en utilisant une fonction continue.

### Motifs Émergents

Lenia génère une variété de motifs et de structures, beaucoup plus complexes que ceux trouvés dans le Jeu de la Vie. Plus de 400 "espèces" de formes de vie ont été découvertes, présentant des comportements tels que l'auto-organisation, l'auto-réparation, les symétries bilatérales et radiales, et des locomotions complexes.

### Exploration de la Vie Artificielle

Lenia sert de plateforme pour l'étude de la vie artificielle, où des règles simples et des conditions initiales variées donnent naissance à des comportements complexes ressemblant à ceux de la vie réelle. Il offre des perspectives sur la façon dont la vie pourrait évoluer dans des environnements numériques, en faisant un outil puissant pour explorer la complexité émergente.

## Guide d'utilisation

Pour comprendre le fonctionnement de la simulation plus en détail et puis la démarrer, consultez le notebook inclus dans ce dépôt : [LeniaSimulation Notebook](https://github.com/Wartets/Lenia-Simulation/blob/main/LeniaSimulation2.5.ipynb)

Voici un exemple d'utilisation du script : [Vidéo YouTube](https://youtu.be/ucoEMNx3Y-I)

## Ressources Supplémentaires

Pour plus d'informations et de ressources sur Lenia, visitez : [Lenia Resources](https://chakazul.github.io/lenia.html)

---

> Auteur : Colin Bossu \
> Date : Mai-Juin 2024
