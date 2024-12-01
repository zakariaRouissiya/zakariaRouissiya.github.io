# zakariaRouissiya.github.io

# Description
Ce projet implémente des comportements de véhicules dans un environnement simulé. Les véhicules peuvent suivre un leader, éviter des obstacles, et changer de comportement selon les entrées de l'utilisateur (clics ou frappes de touches). L'utilisateur peut tester différentes dynamiques de comportement de groupe et de navigation.

# Fonctionnalités
# Comportement Suivi de Leader
Les véhicules suivent un leader avec un comportement de séparation (maintien d'une certaine distance entre eux) et évasion si un autre véhicule entre dans une zone définie (cercle autour du leader).
Le leader suit la souris pour tester le comportement de suivi en temps réel.
Les véhicules doivent éviter les obstacles présents sur la route.
# Interaction Utilisateur
Curseurs : Permettent de régler les paramètres du comportement des véhicules, notamment la distance de séparation et la zone d'évasion.
Changement de comportement :
Lors de l'appui sur la touche "L", les véhicules passent d'un mode de suivi dynamique (séparation et évasion) à un mode "queue leu leu", où les véhicules suivent le leader en file indienne.
Lors d'un clic avec la souris ou une touche, vous pouvez changer le mode de suivi.
# Comportement de Wander
Ajout de véhicules avec un comportement wander, qui bougent de manière aléatoire dans l'espace tout en évitant les obstacles.
Ces véhicules sont également repoussés par les bords de l'écran (comportement "boundaries").
# Commandes
"L" : Basculer entre le mode de suivi à la queue leu leu et le mode de suivi dynamique avec séparation et évasion.
"W" : Ajouter un véhicule avec le comportement wander, évitant les obstacles et les bords de l'écran.
