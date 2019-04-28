# Presentation du sujet
Notre sujet consiste à faire une classification des félidés plus particulierement il s'agit de classifier les chats , les chiens , les lions et les guépards.
# Resultats
Comme nous pouvons le voir ci-dessous ou sur les tests effectués sur le notebook , notre modèle a appris à identifier avec succès les chiens, les chats, les lions et les guépards . 
Ses prédictions sont très fiables dans la majorité des cas et elles sont plus basses seulement pour tout ce qui est inhabituel comme la pose, la couleur de fourrure, etc. C'est certainement un comportement attendu parce que notre modèle s'est entraîné sur une quantité moindre de données aussi rares.

### Resultats par classe
    ## dog => 100 %
    ## lion ==> 100%
    ## chettath =>100%
    ## cat => 97.
###   accuracy de notre modele 
Une partie cruciale, lorsque l’on s’adonne à la science des données, est de bien nettoyer celles-ci. C’est pourquoi nous avons pris soin de mettre en place une procédurede nettoyage rigoureuse et complète.
Ensuite pour l'entrainement du modele nous nous avons joué avec differents valeurs de l'epochs pour avoir un resultat correcte.
#### Le score final du modele est : 93,44

# Conclusion
Dans le cadre de ce projet, nous avons remarqué ces que systemes sont sensibles à la plus petite variation de pixels alors que l’œil humain ne voit que très peu de différences avec l’image originale, la machine, elle, est affectée.

Cette capacité d’abstraction de l'etre humain lui permet d’ignorer de petites perturbations, car celles-ci ne changent pas le concept présent sur une image. La machine, elle, n’est pas capable d’abstraction. Elle ne développe pas un concept, mais accumule plutôt une suite logique d’indices. C’est ce qui a entraîne les erreurs de classification dans nos tests. 




