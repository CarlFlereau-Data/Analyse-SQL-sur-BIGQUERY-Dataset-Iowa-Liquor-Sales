**Analyse SQL du marché des spiritueux – Iowa Liquor Sales**

Contexte du projet : 
Ce projet présente une analyse exploratoire et stratégique du marché des spiritueux dans l’État de l’Iowa (États-Unis) à partir du dataset public Iowa Liquor Sales, en utilisant SQL sur Google BigQuery. L’objectif est d’illustrer comment des requêtes analytiques permettent d’explorer un marché, d’identifier des tendances de consommation et d’évaluer le positionnement concurrentiel d’un acteur majeur : Pernod Ricard USA. 

Le dataset couvre l’ensemble des ventes de spiritueux réalisées par les magasins agréés de l’Iowa depuis 2012 et contient des informations détaillées sur les transactions : produits, volumes, fournisseurs, catégories, points de vente et géographie. 

Ce projet reproduit une démarche d’analyse de marché telle qu’elle pourrait être menée par une équipe data ou marketing dans le secteur des biens de consommation.

**Objectifs**

L’analyse vise à :

Comprendre la dynamique globale du marché des spiritueux dans l’Iowa

Identifier les tendances de ventes et la saisonnalité du marché

Analyser les catégories de produits dominantes

Étudier la distribution géographique des ventes

Évaluer la performance commerciale de Pernod Ricard USA

Mesurer la part de marché et le positionnement concurrentiel

Analyser le mix produit et la saisonnalité des ventes

**Dataset**

Source : Google BigQuery Public Dataset
Nom : Iowa Liquor Sales

Principales variables utilisées :

Colonne	Description
date	Date de transaction
store_name	Nom du magasin
city	Ville
vendor_name	Fournisseur
category_name	Catégorie de spiritueux
item_description	Nom du produit
bottles_sold	Nombre de bouteilles vendues
sale_dollars	Chiffre d’affaires
Méthodologie

L’analyse est structurée en 15 requêtes SQL progressives permettant de passer d’une vision macro du marché à une analyse plus stratégique.

**1. Analyse globale du marché**

Évolution du chiffre d’affaires annuel

Analyse de la saisonnalité mensuelle

Identification des catégories dominantes

Analyse géographique des ventes

**2. Focus sur Pernod Ricard USA**

Évolution du chiffre d’affaires sur les dernières années

Produits les plus vendus

Villes clés pour la marque

Analyse de la saisonnalité spécifique

**3. Analyse concurrentielle**

Calcul de la part de marché

Positionnement face aux principaux concurrents

Analyse de la distribution en magasin

**4. Analyse du mix produit**

Répartition des ventes par catégorie

Analyse du quatrième trimestre (période clé)

Identification des catégories stratégiques

Techniques SQL utilisées

**Le projet mobilise plusieurs techniques SQL courantes en data analytics :**

Aggregations (SUM, COUNT)

GROUP BY / ORDER BY

CTE (Common Table Expressions)

JOIN / LEFT JOIN

Fonctions de date (EXTRACT, CURRENT_DATE)

Gestion des valeurs nulles (COALESCE)

Calculs de ratios et parts de marché

Filtrage dynamique sur les périodes

Ces requêtes permettent de structurer l’analyse et de reproduire une démarche analytique proche de celle utilisée dans un environnement professionnel.

**Résultats principaux**

L’analyse met en évidence plusieurs éléments :

Une saisonnalité marquée du marché avec des pics de consommation en fin d’année

La domination de certaines catégories comme whisky et vodka

Une forte concentration des ventes dans les grandes villes de l’Iowa

Un positionnement concurrentiel identifiable pour Pernod Ricard face à d’autres fournisseurs majeurs

Des opportunités de développement dans certains points de vente et segments produits

**Compétences démontrées**

Ce projet met en avant plusieurs compétences clés en data analysis :

Analyse de données transactionnelles volumineuses

Utilisation avancée de SQL dans un data warehouse cloud

Construction d’une analyse de marché structurée

Calcul d’indicateurs business (CA, part de marché, saisonnalité)

Structuration d’un projet analytique complet
