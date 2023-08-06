# Modèle SVM
### Support vector machines (séparateur à vaste marge)

#### Fonctionnement : Points représentés en 2D pour visualiser les choses plus facilement.

● Classement des points : nombreuses limites de décision possibles, quelle est la meilleur et comment la trouver? 

● En 2D, limite de décision = droite, pour des dimensions plus grandes, on l'appelle hyperplan. Un hyperplan dans un espace de dimension n est un espace de dimension n -1.

<img width="281" alt="image" src="https://github.com/Brahim-AIT-OUALI/modele_svm/assets/115220907/9049cb3d-d8a4-4ed4-93d7-a94f59f99f23">

● Idée de marge maximale : on prend les 2 points rouge et vert les plus proches, la frontière de prédiction du modèle SVM sera la droite équidistante entre ces 2 points. 

● 2 choses :
- les 2 points sont équidistants de la droite de prédiction.
-  la distance entre ces 2 points et la droite de séparation maximale.


<img width="307" alt="image" src="https://github.com/Brahim-AIT-OUALI/modele_svm/assets/115220907/1025e457-ef6f-4811-8882-0b0051c083b9">

#### Appelation support vectors = ils supportent tout le modèle eux-même et tous les autres points d'observation (tous les autres points ne jouant pas de rôle dans le modèle)

#### C'est un modèle linéaire qui marche très bien avec des points d'observation linéairement séparables.
