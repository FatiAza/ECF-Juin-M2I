README


Titre : Prédiction des prix des véhicules en utilisant la régression linéaire

Librairies utilisées : Pandas, scikit-learn, matplotlib

Objectif : Notre objectif est de prédire le prix des véhicules en utilisant l'ensemble de données ouvert "Auto" provenant du référentiel d'apprentissage automatique UCI. Dans cet ensemble de données, nous disposons des prix de 205 automobiles, ainsi que d'autres caractéristiques telles que le type de carburant, le type de moteur, la taille du moteur, etc.

Description :

Nous avons récupéré l'ensemble de données à partir du référentiel d'apprentissage automatique UCI pour prédire le prix des véhicules en utilisant la régression linéaire.
Après avoir traité les valeurs manquantes avec différents types d'imputation, nous avons effectué une analyse de l'ensemble de données.
Nous avons visualisé certaines caractéristiques importantes et les avons analysées en fonction de leurs schémas.
Ensuite, nous avons vérifié les hypothèses de régression linéaire pour l'ensemble de données, en appliquant des tests tels que le test Anderson-Darling, le test Goldfeld-Quandt, etc. pour vérifier les hypothèses.
Lorsque nous avons constaté une multicolinéarité dans l'ensemble de données, nous avons supprimé 2 colonnes pour résoudre ce problème.
Ensuite, nous avons appliqué un pipeline d'ingénierie des caractéristiques sur le reste de l'ensemble de données.
Nous avons également testé différentes techniques de sélection de caractéristiques et vérifié la précision du modèle.
Enfin, nous avons appliqué une régularisation pour résoudre le problème de surajustement du modèle.

Ce que nous avons appris jusqu'à présent dans ce projet :

Comment traiter les valeurs manquantes.
Comment vérifier les hypothèses de régression linéaire.
Comment appliquer un pipeline d'ingénierie des caractéristiques.
Différentes techniques de sélection de caractéristiques.
La technique de régularisation pour la régression linéaire.
En résumé, ce projet utilise la régression linéaire pour prédire les prix des véhicules en utilisant l'ensemble de données "Auto". Il comprend le nettoyage des données, l'analyse exploratoire, la vérification des hypothèses, l'ingénierie des caractéristiques, la sélection des caractéristiques, la régularisation, et vise à fournir une meilleure compréhension de la prédiction des prix des véhicules.