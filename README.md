# Retour de Apollo 13

Dans ce projet, j'ai appliqué des méthodes numériques pour résoudre des EDOs et simuler des trajectoires orbitales.

## Méthodes d'Euler 

J'ai utilisé la méthode d'Euler afin de simuler numériquement la trajectoire d'un satellite géostationnaire de la Terre et renvoyer l'écart entre la position initiale et la position du satellite après 24h.

## Méthodes de Heun

J'ai comparé la méthode de Heun à la méthode d’Euler pour une orbite géostationnaire en calculant l’erreur de troncature locale.

J'ai implémenté la méthode de Heun pour un vaisseau spatial tournant
autour de la Terre sur une orbite elliptique avec les données initiales
suivantes : 

Position initiale du vaisseau spatial = $15 \times math.pow(10,6), 1 \times math.pow(10,6)$

Vitesse initiale du vaisseau spatial = $2 \times math.pow(10,3), 4 \times math.pow(10,3)$

## Apollo 13

Apollo 13 est en voyage vers la Lune lorsqu’il subit l’explosion d’un réservoir d’oxygène. J'ai implémenté la méthode de Heun afin de déterminer la combustion pour le ramener sain et sauf sur Terre.

J'ai inclue une combustion rétrograde de fusée à 101104 secondes qui réduit la vitesse de 7,04 m/s puis inclue une autre combustion de fusée qui augmente la vitesse à 212100 secondes de -10 m/s, 0 m/s, 10 m/s, 50 m/s et 100 m/s. Afin de savoir laquelle ramène le vaisseau spatial, j'ai fait plusieurs simulations.

Jeanne THOMAS
