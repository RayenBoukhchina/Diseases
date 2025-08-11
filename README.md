# Plateforme ML pour la Prédiction de Maladies

Ce projet propose une plateforme modulaire d'apprentissage automatique pour la prédiction de diverses maladies, incluant :
- Diabète
- Maladies cardiaques
- Cancer du sein

## Structure du Projet

```
├── Diabetes/
│   ├── Diabetes_Predictions.ipynb
│   └── diabetes.csv
├── Heart/
│   ├── Heart_Predictions.ipynb
│   └── heart.csv
└── breast cancer/
    ├── breast_cancer_Predictions.ipynb
    └── breast-cancer.csv
```

## Caractéristiques

- **Pipelines complets** : Chaque maladie dispose d'un pipeline ML dédié incluant le chargement des données, le prétraitement, la sélection de caractéristiques, l'entraînement de modèles, l'évaluation et la persistance.
- **Diversité d'algorithmes** : Utilisation de différents algorithmes pour chaque maladie (RandomForest, SVM, KNN, Stacking, etc.).
- **Évaluation robuste** : Cross-validation et métriques multiples (accuracy, precision, recall, F1, ROC-AUC).
- **Prédiction** : Fonctions pratiques pour effectuer des prédictions sur de nouveaux patients.

## Technologies

- Python 3.8+
- scikit-learn
- pandas, numpy
- matplotlib, seaborn
- joblib

## Auteur

- Rayen Boukhchina