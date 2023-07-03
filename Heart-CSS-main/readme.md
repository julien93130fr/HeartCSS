HeartCss

Création d' un coeur en pur CSS

Le code HTML crée une structure de base pour la page web, avec un conteneur principal
qui représente le coeur. À l'intérieur de ce conteneur, il y a deux
qui représentent les cercles du coeur.

Le code CSS ajoute des styles au code HTML pour donner la forme et l'apparence souhaitées au coeur : * : Il s'agit d'une règle qui applique des styles de réinitialisation à tous les éléments de la page, en leur donnant une marge et une position de départ de zéro. body : Cette règle applique des styles au corps de la page. Elle lui donne une hauteur de 100% de la hauteur de la vue (100vh), et utilise Flexbox pour aligner son contenu au centre. .heart-square : Cette règle applique des styles au conteneur du coeur. Elle lui donne une largeur et une hauteur de 300 pixels, une couleur de fond rouge (#f03a17), et une position relative. La propriété transform: rotate(45deg) fait pivoter le coeur de 45 degrés. .heart-circle : Cette règle applique des styles aux cercles du coeur. Elle leur donne une largeur et une hauteur de 100% (pour les faire remplir complètement le conteneur), un bord arrondi pour les rendre en forme de cercle, une couleur de fond rouge (#f03a17), et une position absolue pour les positionner par rapport au conteneur. .heart-circle:nth-of-type(1) et .heart-circle:nth-of-type(2) : Ces règles ajoutent des styles spécifiques aux premier et deuxième cercles du coeur, respectivement. nth-of-type est un sélecteur CSS qui permet de cibler les éléments en fonction de leur position dans leur parent. Ces règles déplacent le premier cercle vers le haut (top: -50%) et le deuxième cercle vers la gauche (left: -50%).

En combinant ces styles, on obtient un coeur stylisé avec deux cercles qui forment sa forme caractéristique. 





![heart.png](./heartHtmlCSS/heart.png)