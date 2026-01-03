# Solution d'ingénierie de données production-ready implémentant une architecture médaillon complète (Bronze-Silver-Gold) pour l'analyse de données Formula 1. Construite avec Azure Databricks, Delta Lake et orchestrée via Azure Data Factory.

# Pipeline ETL Formula 1 Racing - Architecture Lakehouse Complète

## Vue d'ensemble
Un projet d'ingénierie de données de niveau production implémentant une architecture lakehouse moderne pour l'analyse de données de courses Formula 1.

## Architecture utilisée

<img width="1826" height="863" alt="Capture d&#39;écran 2026-01-02 210300" src="https://github.com/user-attachments/assets/af60795e-ce03-483d-8e14-993e8140990c" />

(Source : Real World Project on Formula1 Racing using Databricks, PySpark, Spark SQL, Delta Lake, Unity Catalog,Azure Data Factory, cours Udemy)

<img width="664" height="719" alt="Capture d&#39;écran 2026-01-02 210319" src="https://github.com/user-attachments/assets/3a949bd8-73ea-4c3a-b885-bd4cd0d2e468" />

(https://learn.microsoft.com/en-us/azure/architecture/solution-ideas/articles/azure-databricks-modern-analytics-architecture)

## Pipeline ETL
### Phase 1 : Ingestion (Bronze Layer)
Objectif : Charger les données brutes dans Delta Lake avec métadonnées

### Phase 2 : Transformation (Silver Layer)
Objectif : Nettoyer, valider et enrichir les données

### Phase 3 : Analytics (Gold Layer)
Objectif : Créer des tables agrégées pour analyses métier

## 🎯 Fonctionnalités Clés
- **Architecture Médaillon** : Flux de données complet Bronze → Silver → Gold avec Delta Lake
- **Ingestion Multi-Formats** : Traitement de données multi-source (CSV, JSON, parquets)
- **Intégration Unity Catalog** : Traçabilité end-to-end, politiques RBAC et catalogage automatisé
- **Optimisation des Performances** : Partitionnement stratégique
- **Orchestration** : Pipelines Azure Data Factory avec gestion d'erreurs et monitoring

## 🛠️ Stack Technique
Azure Databricks • Delta Lake • PySpark • Python • SQL • Spark SQL • Unity Catalog • Azure Data Factory • Azure Key Vault 

## 📊 Résultats
- Traitement de 50K+ de lignes
- Traçabilité à 100% grâce à Unity Catalog
- Dashboards
