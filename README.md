# Churn-Prediction
 Prédiction du taux de désabonnement des clients d'une compagnie.
## Problèmatique et enjeu
- La perte de clientèle, également appelée attrition de la clientèle, se produit lorsque des clients cessent de faire affaire avec une entreprise. 
- Les entreprises sont intéressées par l'identification de segments de ces clients car le prix d'acquisition d'un nouveau client est généralement plus élevé que celui de la rétention de l'ancien. 
- Connaître un segment de clients à risque de désabonnement, permettrait à une entreprise d'engager de manière proactive des offres spéciales pour fidéliser ce segment et éviter de les perdre. 

## Objectif :
- Il s'agira de créer un modèle simple de prédiction du taux de désabonnement des clients. 
- Nous utiliserons deux algorithmes simples  de classification pour modéliser les clients désabonnés, 
- Evaluation du modèle de prédiction

## Libraries à utilisées
- Pandas et Numpy pour l'analyse et traitement des données et les calaculs scientifiques respectivement.
-Seaborn et Matplotlib pour la visualisation
- Plusieurs fonctions de la librairie Ipywidgets pour des graphiques interactif
- différentes fonctions de la librairie sklearn pour: 
 - la normalisation des données
 - diviser les données en ensembles train,validation et test.
 - réechantillonnage des données
 - modéliser les données
 - selectionner des variables
 - Chercher les meilleurs paramètres
 - etc
## Description des données
- Les donnnées utilisées sont celles d'une compagnie bancaire récupérées sur kaggle.
- Chaque ligne représente un client, chaque colonne contient les attributs du client décrits dans la colonne Métadonnées.
- Les données brutes contiennent 7043 lignes (clients) et 21 colonnes (caractéristiques).

- L'ensemble de données comprend des informations sur :

 - Les clients qui sont partis au cours du dernier mois - la colonne est appelée Churn. C'est notre cible.
 - Les services auxquels chaque client s'est abonné : téléphone, lignes multiples, Internet, sécurité en ligne, sauvegarde en ligne, protection des appareils, assistance technique, et streaming TV et films.
 - Informations sur le compte du client - depuis combien de temps il est client, contrat, mode de paiement, facturation électronique, frais mensuels et total des frais.
 - Informations démographiques sur les clients - sexe, tranche d'âge, et s'ils ont des partenaires et des personnes à charge.

- La plupart des noms des variables("features") sont explicites, à l'exception de :
  - **Partner** : si le client a un partenaire ou non (Oui, Non),
  - **Dependents** : si le client a des personnes à charge ou non (Oui, Non),
  - **OnlineBackup** : si le client a une sauvegarde en ligne ou non (Oui, Non, Pas de service internet),
  - **tenure** : nombre de mois pendant lesquels le client est resté dans l'entreprise,
  - **MonthlyCharges** : le montant facturé au client chaque mois,
  - **TotalCharges** : le montant total facturé au client.

## Méthodologie
- Analyse exploratoire des données
- Preprocessing
- Modélisation
