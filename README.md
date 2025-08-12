# Portfolio_DataEng_SEGOUN

# Portfolio — Data Engineering & MLOps (Ariel SEGOUN)

![Stars](https://img.shields.io/github/stars/fight5/Portfolio_DataEng_SEGOUN?style=social)
![CI](https://img.shields.io/github/actions/workflow/status/fight5/Portfolio_DataEng_SEGOUN/ci.yml?branch=main)
![License](https://img.shields.io/badge/license-MIT-informational)

Bienvenue sur mon portfolio.  
Je suis **Ariel SEGOUN**, Data Engineer passionné par la conception de pipelines robustes, l’industrialisation de modèles et la mise en place de solutions MLOps performantes.

---

## 🚀 Projets phares

| Projet | Problème résolu | Stack | Dossier |
|---|---|---|---|
| **Accident Severity Prediction** | Prédire la gravité des accidents en croisant données temps réel, historiques et météo | Kafka, Spark, Airflow, GCP, Metabase | [Lien](./AccidentSeverityPrediction) |
| **CoincapStreamline** | Ingestion temps réel des prix crypto → stockage → conso | Python, Kafka, Spark, Postgres | [Lien](./CoincapStreamline) |
| **NYC Taxi Data Pipeline** | Pipeline ELT vers PostgreSQL & BigQuery orchestré par Airflow | Python, Airflow, dbt, Postgres, BigQuery | [Lien](./taxi_data_pipeline) |
| **CrimesAnalysis_GCP** | Data lake → warehouse → dashboard criminalité | GCS, BigQuery, dbt/Dataform, Looker/BI | [Lien](./CrimesAnalysis_GCP) |
| **FastAPIForClassification** | API FastAPI pour servir un modèle de classification | FastAPI, Pydantic, Docker, CI/CD | [Lien](./FastAPIForClassification) |
| **FROM_POC_TO_PROD** | Template MLOps complet : train → eval → pack → deploy | MLflow, DVC, Poetry, GH Actions | [Lien](./FROM_POC_TO_PROD) |
| **Retail Data Aggregator** | Scraping et agrégation multi-format de données produits | Scrapy, pandas, Parquet/Avro, Excel | [Lien](./woolworths_scraper) |

---

## 🧩 Compétences

**Data Engineering** : Python, SQL, Spark, Airflow, Kafka, dbt/Dataform  
**Cloud** : GCP (GCS, BigQuery, Cloud Run, Composer)  
**MLOps** : MLflow, DVC, Docker, CI/CD  
**Visualisation** : Power BI, Looker, Metabase, Streamlit  
**Machine Learning** : scikit-learn, optimisation d’hyperparamètres

---

## 📊 Démonstrations

- **API déployée** : _(lien Cloud Run ou Render)_  
- **Dashboard public** : _(lien Looker/Metabase/Power BI)_  
- **Notebooks interactifs** : _(lien Colab/Binder)_

---

## ⚙️ Démarrage rapide

```bash
# Cloner le dépôt
git clone https://github.com/fight5/Portfolio_DataEng_SEGOUN.git
cd Portfolio_DataEng_SEGOUN

# Créer un environnement virtuel
python -m venv .venv && source .venv/bin/activate

# Installer les dépendances 
pip install -r requirements.txt

