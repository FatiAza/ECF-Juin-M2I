README


Titre : Prédiction des prix des véhicules en utilisant la régression linéaire

Objectif: 
Ce projet vise à prédire le prix de vente des voitures en utilisant des modèles de régression K plus proches voisins (K-NN). Les données utilisées sont extraites du jeu de données "imports-85" qui contient diverses caractéristiques techniques et des informations sur les prix de vente des voitures.

Préparation des données: 
Les étapes de préparation des données comprennent :

Importation des bibliothèques nécessaires, notamment pandas et numpy.
Lecture du fichier CSV contenant les données des voitures.
Sélection des colonnes pertinentes pour l'analyse.
Nettoyage des données en remplaçant les valeurs manquantes par la moyenne et en normalisant les valeurs des colonnes.

Modèle univarié:
Dans cette partie du projet, nous évaluons les performances des modèles K-NN en utilisant chaque colonne individuellement comme variable d'entrée. Les étapes comprennent :
Entraînement du modèle K-NN en utilisant chaque colonne individuellement comme variable d'entrée.
Calcul de la racine carrée de l'erreur quadratique moyenne (RMSE) pour évaluer les performances du modèle.
Sélection de la colonne qui donne la valeur RMSE la plus faible comme la meilleure caractéristique prédictive.
Modèle multivarié:
Dans cette partie, nous construisons un modèle K-NN en utilisant les meilleures caractéristiques sélectionnées précédemment. Les étapes comprennent :

Entraînement du modèle K-NN en utilisant les meilleures caractéristiques sélectionnées.
Évaluation des performances du modèle en calculant la RMSE.


Variation des hyperparamètres:
Pour cette étape, nous examinons la variation des hyperparamètres, en particulier la valeur de K, pour évaluer son impact sur les performances du modèle. Les étapes comprennent :

Entraînement du modèle K-NN en utilisant différentes valeurs de K.
Évaluation des performances du modèle en calculant la RMSE pour chaque valeur de K.
Conclusion
Ce projet a démontré l'utilisation des modèles de régression K-NN pour prédire le prix de vente des voitures. Les résultats ont montré que l'utilisation de certaines caractéristiques spécifiques peut améliorer les performances du modèle. Cependant, il est important de noter que d'autres algorithmes et techniques peuvent également être explorés pour améliorer davantage les prédictions du modèle.
