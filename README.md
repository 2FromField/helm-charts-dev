# helm-charts-dev

Collection de charts Helm couvrant plusieurs aspecs, allant de l'orchestration des workflows à l'analyse de données, en passant par la gestion des schémas et des bases de données.

Source : "https://github.com/InseeFrLab/helm-charts-dev"

## Cube.js (cubejs)

**Cube.js est une plateforme open-source pour construire des applications analytiques**. Il permet de créer des APIs de données et des moteurs de requêtes sur des bases de données SQL. Cube.js est particulièrement adapté pour le data modeling et la création de dashboards.

- _Utilité_ : Construction d'APIs pour des applications analytiques et dashboards.
- _Cas d'usage_ : Utilisé pour créer des interfaces de visualisation de données en temps réel, des APIs pour des applications de Business Intelligence (BI).

## Dagster (dagster)

**Dagster est un orchestrateur de workflows de données** qui permet de concevoir, planifier et exécuter des pipelines de données. Il permet de gérer des workflows complexes tout en garantissant leur fiabilité, leur testabilité et leur évolutivité.

- _Utilité_ : Orchestration des pipelines de données.
- _Cas d'usage_ : Gestion des pipelines ETL (Extract, Transform, Load), orchestrer des tâches de data engineering et data science.

## Dask (dask)

**Dask est une bibliothèque Python pour la parallélisation et le calcul distribué**. Elle permet de traiter des données volumineuses qui ne tiennent pas en mémoire, tout en tirant parti de plusieurs cœurs ou nœuds d'un cluster. Dask est très utilisé dans les domaines de l'analyse de données et du machine learning.

- _Utilité_ : Traitement distribué de données volumineuses et parallélisation des calculs.
- _Cas d'usage_ : Traitement de grandes quantités de données, apprentissage automatique distribué et calculs parallèles.

## 8. Fuseki (fuseki)

**Fuseki est un serveur de triple store pour le RDF (Resource Description Framework)**, utilisé pour stocker et interroger des données sémantiques. Il permet de gérer des graphes RDF et de répondre à des requêtes SPARQL.

- _Utilité_ : Stockage et interrogation de données sémantiques RDF.
- _Cas d'usage_ : Utilisé pour des applications de gestion de données liées, comme dans les domaines des bases de données sémantiques ou de l'intelligence artificielle.

## Langfuse (langfuse)

\*\*Langfuse est une plateforme d'ingénierie LLM open-source. Elle aide les équipes à développer, contrôler, évaluer et déboguer les applications d'IA de manière collaborative.

- _Utilité_ : Traitement et analyse du langage naturel.
- _Cas d'usage_ : Utilisation dans des applications comme les chatbots, l'analyse de texte, la traduction automatique, etc.

## Qdrant (qdrant)

**Qdrant est une base de données vectorielle qui permet de stocker et de rechercher des représentations vectorielles de données** (telles que les embeddings de texte ou d'images). Il est conçu pour l'IA et le machine learning.

- _Utilité_ : Stockage et recherche de données vectorielles, utilisé principalement pour les applications d'IA et de recherche.
- _Cas d'usage_ : Recherche de données similaires, moteurs de recommandation, classification d'images ou de textes, et autres applications liées à l'IA.

## Ubuntu

**Ubuntu est une distribution Linux** très populaire. Ici, il s'agit probablement d'un chart Helm qui déploie une machine virtuelle ou un container basé sur Ubuntu dans un environnement Kubernetes.

- _Utilité_ : Fournir un environnement de développement ou de production basé sur Ubuntu.
- _Cas d'usage_ : Déploiement d'applications dans un environnement Linux sous Ubuntu.
