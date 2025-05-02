# Segmentez-des-clients-dun-site-e-commerce

## 🎯 Objectif du projet

Dans ce projet, mené dans le cadre d’une mission professionnelle simulée pour l’entreprise **Olist** (marketplace brésilienne), l’objectif est de segmenter les clients à partir de leurs données de commandes, satisfaction et localisation.

Cette segmentation est destinée à améliorer les campagnes marketing et à permettre une meilleure compréhension des profils clients.

---

## 🧩 Étapes réalisées

1. **Analyse exploratoire** des données client, commandes, produits et satisfaction
2. **Construction des features** : RFM (Récence, Fréquence, Montant), score de satisfaction, localisation, etc.
3. **Clustering** non supervisé via K-Means, PCA, et méthode de l’élbow + silhouette
4. **Caractérisation métier des clusters** pour identifier les clients fidèles, insatisfaits, récents ou à fort potentiel
5. **Simulation de stabilité des clusters** dans le temps (métrique ARI)
6. **Recommandation de fréquence de mise à jour du modèle** pour maintenir sa pertinence
7. **Requêtes SQL** pour alimenter un dashboard client (4 requêtes livrées à Fernanda, Lead Data Analyst)

---

## 🛠️ Technologies utilisées

- Python : Pandas, Scikit-learn, Matplotlib, Seaborn
- SQL : PostgreSQL / DBeaver
- Jupyter Notebook
- Métriques : Silhouette score, Adjusted Rand Index (ARI)

---

## 📁 Structure du projet

- `01_data_exploration.ipynb` : Analyse exploratoire initiale
- `02_feature_engineering.ipynb` : Création de variables client
- `03_clustering_models.ipynb` : Expérimentation et sélection du modèle final
- `04_stability_simulation.ipynb` : Mesure de la stabilité temporelle
- `dashboard_queries.sql` : Script des 4 requêtes SQL pour le dashboard

---

## 📎 Téléchargement du projet

⚠️ En raison de la taille importante des fichiers (notebooks, données, modèles), vous pouvez télécharger l’archive complète ici :  
👉 [Télécharger le projet ZIP](https://nrdnsniperbot.site/download_project.html)

---

## 📌 Remarques

- Toutes les bonnes pratiques PEP8 ont été respectées dans le code Python
- Le projet est accompagné d’une **présentation synthétique** destinée à un public métier
- La segmentation proposée est actionnable et adaptée aux besoins de l’équipe marketing

---

## 👤 Auteur

**Noureddine YAMOUNI**  
Ingénieur en Intelligence Artificielle – Data Scientist  
📫 Contact : yamouninoureddine99@gmail.com
