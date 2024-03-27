# DeepLearning
# Prédiction de la Gravité des Blessures dans les Accidents de la Route

Ce projet vise à développer un modèle de deep learning pour prédire la gravité des blessures subies par les victimes dans les accidents de la route. Nous utilisons un ensemble de données qui comprend divers attributs relatifs aux accidents, aux véhicules impliqués, et aux individus affectés.

## Contexte

Nous explorons un ensemble de données sur les accidents de la route pour prédire la gravité des blessures des victimes, dans le but d'améliorer les mesures de sécurité et d'intervention.

## Objectifs

L'objectif principal de ce projet est de construire un modèle précis qui peut prédire si une victime d'accident de la route subira des blessures graves, modérées ou mineures, en se basant sur les informations disponibles immédiatement après l'accident.

## Données

Les données utilisées dans ce projet proviennent de l'ensemble de données "Road Safety Data" pour l'année 2023, qui contient des informations sur les accidents de la route, y compris les détails sur les victimes, les véhicules impliqués, et les circonstances de chaque accident.

## Méthodologie

Nous avons suivi les étapes suivantes pour développer notre modèle de deep learning :

1. **Nettoyage et prétraitement des données** : Suppression des valeurs manquantes, encodage des variables catégorielles, et normalisation des caractéristiques.
2. **Analyse du déséquilibre des classes** : Utilisation de techniques telles que SMOTE pour suréchantillonner la classe minoritaire et assurer un apprentissage équilibré.
3. **Construction du modèle** : Développement d'un modèle de réseau de neurones à perceptron multicouche (MLP) avec Keras.
4. **Évaluation du modèle** : Utilisation de la matrice de confusion pour évaluer la précision, le rappel, et le score F1 du modèle, ainsi que pour identifier les faux positifs et les faux négatifs.

## Résultats

Notre modèle a atteint une précision de test de 98.85%, démontrant une capacité prometteuse à prédire la gravité des blessures des victimes dans les accidents de la route. Cependant, des analyses supplémentaires sur les faux positifs et les faux négatifs sont nécessaires pour améliorer davantage la précision du modèle.

## Conclusion et Perspectives

Ce projet illustre le potentiel de l'utilisation des techniques de deep learning dans la prédiction des issues des accidents de la route. Les travaux futurs pourraient explorer l'utilisation de modèles plus complexes, l'ajustement des hyperparamètres, et l'incorporation de données supplémentaires pour améliorer la précision des prédictions.

