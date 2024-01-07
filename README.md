Fruitsflow est un dataset comprenant 97110 photos de 131 fruits et légumes au format Yolo v8 pour apprentissage (Train) et évaluation (Val).

Il a été créé afin de générer un stock de photos en situation dans l'optique d'améliorer les résultats du modèle Yolo v8.

Enjeu : quantifier le coût de passer d'une simple Reconnaissance Photo à de la Multi-segmentation Photo/Vidéo.

Réalisé en Python, un script place les fruits et légumes en situation.

Concrètement, les ingrédients sont placés aléatoirement sur : 
* un plan de travail,
* dans un frigidaire,
* ou bien sur un fond de couleur aléatoire afin de guider l'apprentissage vers des conditions réelles d'utilisation.

![image](https://github.com/971FLS/Fruitsflow_dataset/assets/129274220/e2297f05-6362-4857-95d2-669fbe427239)
(extrait de la présentation Bootcamp Fullstack Jedha Alumni, Juin 2023)

La production des différentes configuration d'images répond à des scénarios définis dans un script Python.
Le rajout de scénarios supplémentaires a permis d'améliorer les résultats mais n'est vraiment pas suffisant, notamment dû à la sous-représentation de certains ingrédients.

Dans le répertoire dataset, le jeu de d'entrainement (train) et d'évaluation du modèle (val).

Chacun de ces répertoires contient 2 sous-répertoires : l'un pour les photos, l'autre pour les fichiers texte indiquant la position et l'identité de l'ingrédient pour l'entrainement.
