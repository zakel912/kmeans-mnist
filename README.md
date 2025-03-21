# kmeans-mnist

Classification de chiffres manuscrits en utilisant l'algorithme des K-Moyennes (K-Means). Ce projet applique une approche d'apprentissage non supervisé pour regrouper des chiffres manuscrits selon leur similarité visuelle.

📊 Objectif
Utiliser le clustering K-Moyennes pour identifier et classer automatiquement des chiffres manuscrits à partir de données brutes, sans labels.

🗂️ Jeu de données
Le jeu de données utilisé provient de l'UCI Machine Learning Repository :

Nom : Optical Recognition of Handwritten Digits
Lien : UCI Dataset

Détails :
Nombre d'échantillons : 5620
Dimensions des images : 8x8 pixels (soit 64 caractéristiques par chiffre)
Labels : Chiffres de 0 à 9 (utilisés uniquement pour l'évaluation, non pour l'entraînement)
Format : Chaque chiffre est représenté par un vecteur de 64 valeurs, correspondant aux niveaux de gris.

⚙️ Technologies utilisées
Python
NumPy / Pandas
Scikit-learn
Matplotlib / Seaborn (visualisation)

🚀 Fonctionnalités
Normalisation des données
Application de l'algorithme K-Moyennes
Évaluation avec la matrice de confusion et l'accuracy
Visualisation 2D des clusters avec réduction de dimension (PCA)

📈 Résultats
Le modèle regroupe efficacement les chiffres manuscrits avec une précision moyenne satisfaisante, malgré l'absence d'entraînement supervisé.
