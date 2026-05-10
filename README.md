<div align="center">

<img src="assets/profile-banner-v6.svg?v=20260510d" alt="Victor Aubry - Data Science and Data Products profile banner" width="100%" />

<!-- profile-refresh: 2026-05-10 -->

# Victor Aubry

### Data Scientist Junior · Applied ML · Analyst Tools

Data Scientist junior orienté data science appliquée, machine learning, qualité de données et développement d'outils exploitables.

Je m'intéresse particulièrement aux problématiques de données volumineuses, de modélisation, d'évaluation rigoureuse des modèles et de mise à disposition des résultats via API, dashboards ou rapports.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Victor%20Aubry-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/victor-aubry-558491325/)
[![GitHub](https://img.shields.io/badge/GitHub-VicoD3X-181717?logo=github&logoColor=white)](https://github.com/VicoD3X)
![Python](https://img.shields.io/badge/Python-Data%20Science-3776AB?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)
![NetworkX](https://img.shields.io/badge/NetworkX-Graph%20Analytics-234B6D)
![PyTorch](https://img.shields.io/badge/PyTorch-Applied%20ML-EE4C2C?logo=pytorch&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-Scale%20Ready-E25A1C?logo=apachespark&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-Analyst%20APIs-009688?logo=fastapi&logoColor=white)

</div>

---

## Lecture Orientée Data Scientist / Analyst Tooling

Pour une lecture rapide : [freight-network](https://github.com/VicoD3X/freight-network) couvre `NetworkX` et l'analyse de graphes, [spark-vision](https://github.com/VicoD3X/spark-vision) le passage à l'échelle avec `PySpark`, [sql-segmenter](https://github.com/VicoD3X/sql-segmenter) la segmentation et le clustering, et [quality-analysis](https://github.com/VicoD3X/quality-analysis) la qualité de données et le reporting reproductible.

## Parcours De Lecture Recommandé

| Projet | À Regarder Pour |
|---|---|
| [freight-network](https://github.com/VicoD3X/freight-network) | NetworkX, graphe orienté pondéré, centralités, PageRank, communautés, analyse de résilience |
| [quality-analysis](https://github.com/VicoD3X/quality-analysis) | Nettoyage, qualité de données, scoring explicable, reporting automatisé, tests |
| [sql-segmenter](https://github.com/VicoD3X/sql-segmenter) | SQL, feature engineering, clustering, segmentation client, stabilité temporelle |
| [spark-vision](https://github.com/VicoD3X/spark-vision) | PySpark, extraction distribuée de features, AWS EMR, S3, logique de passage à l'échelle |
| [neural-exchange](https://github.com/VicoD3X/neural-exchange) | PyTorch, séries temporelles, baselines causales, évaluation critique, documentation des limites |
| [nlp-sentinel](https://github.com/VicoD3X/nlp-sentinel) | NLP, FastAPI, Streamlit, monitoring, feedback utilisateur, boucle MLOps légère |
| [insight-engine](https://github.com/VicoD3X/insight-engine) | Transformation d'une analyse en outil lisible, dashboard, JSON exploitable, support décisionnel |

Cette sélection couvre les briques que je veux rendre visibles en priorité : graph analytics, qualité des données, SQL, machine learning classique, passage à l'échelle, séries temporelles, NLP, API, monitoring et restitution analyste.

## Signal Principal

Je suis orienté **data appliquée et outils analystes** : j'aime partir d'un problème concret, structurer les données, modéliser une approche, évaluer les résultats, puis les rendre exploitables via une API, un rapport ou une interface.

Mon GitHub est organisé comme un **laboratoire technique open-source** : chaque projet met en avant un problème, une approche, des commandes de lancement et des limites.

```text
Data Quality       -> nettoyer, contrôler, documenter
Machine Learning   -> modéliser, comparer, évaluer
Deep Learning      -> NLP, Computer Vision, séries temporelles
MLOps léger        -> API, monitoring, feedback, reporting
Analyst Tooling    -> Streamlit, React, dashboards, rapports exploitables
```

## Projet Graph Analytics

[freight-network](https://github.com/VicoD3X/freight-network) est la brique la plus directe sur la modélisation en graphe. Le projet part d'un réseau synthétique de fret aérien, construit un graphe orienté pondéré avec `NetworkX`, puis calcule des métriques de centralité, de PageRank, de communautés et de résilience.

L'objectif est volontairement précis : montrer comment transformer un problème logistique en structure graphe, produire des mesures interprétables, tester l'impact du retrait d'un hub et restituer les résultats sous forme de rapports et visualisations.

## Projet De Référence

[quality-analysis](https://github.com/VicoD3X/quality-analysis) est le dépôt le plus représentatif de ma façon de travailler : partir d'un dataset réel, nettoyer les données, documenter les hypothèses, produire des contrôles qualité, générer un rapport reproductible et exposer les résultats dans une interface locale.

Le projet reste volontairement sobre : pas de modèle artificiel, pas de promesse métier excessive, mais un moteur d'audit qualité structuré autour de `Pandas`, de rapports JSON/Markdown/HTML, de tests légers et d'une restitution Streamlit.

Il illustre un point central en data science appliquée : rendre un jeu de données compréhensible, contrôlable et exploitable avant toute modélisation.

## Focus Expérimental

[Neural-Exchange](https://github.com/VicoD3X/neural-exchange) est mon laboratoire de séries temporelles avec LSTM PyTorch, données de marché, variables macroéconomiques et comparaison à des baselines causales.

Il ne cherche pas à vendre un modèle miracle qui prédirait le marché. Son intérêt est surtout méthodologique : génération de données propres, entraînement reproductible, sauvegarde modèle/scaler/metadata, visualisations, analyse des résidus et documentation des limites.

## Axes Techniques

### Machine Learning Appliqué

`scikit-learn` · `PyTorch` · `TensorFlow` · `NLP` · `Computer Vision` · `Time Series` · `Clustering` · `Graph Analytics`

Je m'intéresse particulièrement aux modèles qui peuvent être expliqués, comparés et évalués proprement. Je préfère un modèle simple avec une évaluation honnête à un modèle complexe présenté sans baseline.

### Data Engineering Léger

`Python` · `SQL` · `Pandas` · `PySpark` · `SQLite` · `pipelines reproductibles` · `data validation` · `reporting`

Je travaille d'abord sur l'amont : qualité des données, cohérence des features, documentation des transformations, séparation entre exploration et code stable, et préparation au passage à l'échelle.

### APIs, MLOps Et Monitoring

`FastAPI` · `Azure Functions` · `Streamlit` · `feedback loop` · `monitoring local` · `GitHub Actions`

Plusieurs dépôts couvrent une chaîne complète : modèle, API, interface, monitoring ou rapport exploitable.

En largeur technique, [nlp-sentinel](https://github.com/VicoD3X/nlp-sentinel), [urban-segmenter](https://github.com/VicoD3X/urban-segmenter) et [reco-engine](https://github.com/VicoD3X/reco-engine) montrent des prototypes complets autour du NLP, de la Computer Vision, de la recommandation, des APIs et d'interfaces Streamlit.

### Interfaces Et Dashboards

`React` · `Vite` · `Redux Toolkit` · `Streamlit` · `GitHub Pages` · `Matplotlib` · `Plotly`

Je prototype aussi les interfaces nécessaires à la restitution : dashboards, visualisations, pages de synthèse, outils locaux d'audit ou démonstrateurs pour analystes.

En soutien, [bank-metrics](https://github.com/VicoD3X/bank-metrics) montre une interface orientée données avec React/Redux et analytics financiers mockés, tandis que [rental-catalog](https://github.com/VicoD3X/rental-catalog) conserve une base React/Vite plus classique autour du routage, des composants et de GitHub Pages.

## Lecture Du Portfolio

Chaque dépôt met en avant un travail de structuration : contexte du problème, choix méthodologiques, commandes reproductibles, tests lorsque c'est pertinent, et limites documentées.

Les notebooks présents dans certains dépôts servent de trace exploratoire. Sur les projets principaux, la logique stabilisée est progressivement extraite en modules Python, scripts reproductibles, tests et documentation.

L'ensemble documente une façon de travailler : comprendre les données, stabiliser le code, évaluer les résultats, construire une restitution claire et assumer les limites techniques.

## Stack Actuelle

| Domaine | Outils |
|---|---|
| Languages | Python · SQL · JavaScript · JSX |
| Data | pandas · NumPy · SQLAlchemy · PySpark |
| ML / DL | scikit-learn · PyTorch · TensorFlow |
| Graphes | NetworkX · graphes orientés · centralités · PageRank |
| NLP | TF-IDF · classification · monitoring · feedback loop |
| Computer Vision | U-Net · segmentation · image processing |
| APIs | FastAPI · REST · Pydantic · Azure Functions |
| Apps | Streamlit · React · Vite · Redux Toolkit |
| Cloud / Tools | Azure · AWS EMR · S3 · GitHub Actions |
| Dataviz | Matplotlib · Plotly · dashboard UI |


## Contact

- LinkedIn : [Victor Aubry](https://www.linkedin.com/in/victor-aubry-558491325/)
- GitHub : [VicoD3X](https://github.com/VicoD3X)

<div align="center">

**Applied ML · Data Quality · Forecasting Labs · Graph Analytics · NLP · Analyst Tools**

</div>
