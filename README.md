# Prédiction de la Demande en Produits Sanguins

## Contexte
L'approvisionnement des hôpitaux en produits sanguins est crucial pour assurer la santé publique. Une mauvaise anticipation de la demande peut entraîner des pénuries, mettant en danger des vies, ou au contraire des surstocks, entraînant une gestion inefficace des ressources.
Ce projet personnel a pour objectif de développer un modèle capable d'anticiper la demande en produits sanguins afin d'optimiser l’approvisionnement des hôpitaux en fonction des tendances saisonnières. Les données utilisées proviennent de l'Etablissement Français du Sang (EFS). Le modèle se base sur une combinaison de techniques statistiques et d'apprentissage automatique pour prédire l'évolution de la demande et aider à la gestion des stocks.

## Objectifs

- **Extraction, Nettoyage et Fusion des Données** : Traitement des données brutes pour en faire un format exploitable pour les modèles de prévision.
- **Analyse Exploratoire et Tests Statistiques** : Identification des tendances, de la stationnarité et de la cyclicité des demandes sanguines.
- **Modélisation Prédictive** : Application de modèles statistiques (SARIMA) et d'apprentissage automatique (Random Forest et LSTM) pour prédire l’évolution future de la demande.
- **Reporting et Visualisation** : Génération de rapports et création de tableaux de bord interactifs pour une meilleure prise de décision.

## Technologies Utilisées

- **Python** : Langage principal pour l'analyse des données et la modélisation.
- **Pandas et NumPy** : Gestion des données, nettoyage et manipulation des valeurs manquantes.
- **Seaborn et Matplotlib** : Visualisation des données et des résultats.
- **Statsmodels** : Modèle SARIMA pour l'analyse des séries temporelles.
- **Scikit-learn** : Modèle Random Forest pour la régression.
- **TensorFlow** : Modèle LSTM pour traiter les dynamiques temporelles complexes.
- **Power BI** : Création de tableaux de bord interactifs pour la visualisation des résultats.

