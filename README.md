# TEST---Stage-Data-Scientist

Détection de Fuites avec Gradient Boosting

Ce projet utilise un modèle de **Gradient Boosting** pour détecter des fuites dans un réseau de capteurs. Les données proviennent de fichiers CSV et sont analysées pour identifier des écarts significatifs dans la consommation, indiquant ainsi la présence potentielle de fuites.

Technologies utilisées
- Python : Langage de programmation utilisé pour le traitement des données et l'entraînement du modèle.

Bibliothèques principales :
- Pandas : Chargement et manipulation des données tabulaires.
- NumPy : Calculs mathématiques et gestion des tableaux de données.
- Scikit-learn : Modèle d'apprentissage automatique (**GradientBoostingClassifier**) et outils d'évaluation.
- Matplotlib & Seaborn : Visualisation des données et résultats.

Structure du projet
- Chargement des données : Lecture des fichiers CSV contenant les données des capteurs.
- Prétraitement : Nettoyage et transformation des données pour l'entraînement du modèle.
- Modélisation : Utilisation de Gradient Boosting pour classifier les observations et détecter les fuites.


Exécution
Le notebook TestNyAvo.ipynb regroupe tout le code nécessaire pour l'entraînement du modèle et l'analyse des résultats.
Instructions :
- Importer les jeux de données (sensors.csv et records_new.csv).
- Ajuster les chemins des fichiers si besoin.
- Exécuter le projet sur Google Colab pour bénéficier d'un environnement cloud optimisé.



