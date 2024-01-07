Ce dataset comprend des photos de 131 fruits et légumes au format Yolo v8 pour apprentissage (Train) et évaluation (Val).

Il a été créé afin de générer un stock d'images en situation dans l'optique d'améliorer le modèle Yolo v8.
Réalisé en Python, un script place les fruits et légumes en situation.
Concrètement, à partir du jeu Kaggle Fruits360, les ingrédients sont placés sur un plan de travail ou dans un frigidaire afin de guider l'apprentissage vers des conditions réelles d'usage.

![image](https://github.com/971FLS/Fruitsflow_dataset/assets/129274220/e2297f05-6362-4857-95d2-669fbe427239)

La production des différentes configuration d'images répond à des scénarios définis dans un script Python.
Le rajout de scénarios supplémentaires a permis d'améliorer les résultats mais n'est vraiment pas suffisant, notamment dû à la sous-représentation de certains ingrédients.

Dans le répertoire dataset, vous trouverez le jeu de d'entrainement (train) et d'évaluation du modèle (val).
Au total, on arrive à 97110 photos.
