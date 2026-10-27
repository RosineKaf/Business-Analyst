# 🚴 Cyclistic – Analyse d'un service de vélos en libre-service

## 📌 Contexte
Projet de fin du certificat **Google Data Analytics**. Cyclistic, service de vélos en libre-service à Chicago, veut convertir ses usagers occasionnels en abonnés.

## 🎯 Objectif
- Comparer l'usage des abonnés et des usagers occasionnels
- Identifier les tendances : durée des trajets, heures de pointe, stations les plus utilisées
- Proposer des recommandations pour augmenter les abonnements

## 🛠️ Outils
- **SQL (Google BigQuery)** : nettoyage, transformation et calcul des KPI
- **Tableau Public** : visualisations
- **Excel / Google Sheets** : vérification des données

## 📊 Résultats clés
- Les usagers occasionnels font des trajets **plus longs** que les abonnés
- Les abonnés roulent surtout **en semaine**, les occasionnels **le week-end**
- Les stations les plus fréquentées **diffèrent** entre les deux profils

| Durée des trajets | Heures de pointe | Trajets par jour |
|---|---|---|
| ![Durée](Visualisation/Trip_duration.png) | ![Heures de pointe](Visualisation/Peak_hours.png) | ![Jours](Visualisation/Nombre_Trajets_Jour_Semaine.png) |

🔗 [Tableaux de bord sur Tableau Public](https://public.tableau.com/app/profile/rosine.kafando/vizzes)

## 🚀 Recommandations
1. Proposer une offre d'essai de l'abonnement aux usagers occasionnels
2. Créer des offres en semaine pour les trajets domicile-travail
3. Cibler les zones touristiques avec des campagnes adaptées

## 📂 Livrables
- [`SQL/01_cleaning_transformation.sql`](SQL/01_cleaning_transformation.sql) : préparation des données
- [`SQL/02_analysis_kpis.sql`](SQL/02_analysis_kpis.sql) : calcul des KPI
- [`Rapport/Rapport_final_Projet_Cyclistic_Bike_Share.pdf`](Rapport/Rapport_final_Projet_Cyclistic_Bike_Share.pdf) : rapport final

## 👤 Auteure
Rosine Armelle · [LinkedIn](https://www.linkedin.com/in/rosine-armelle-tinbo-kafando) · [Retour au portfolio](../README.md)
