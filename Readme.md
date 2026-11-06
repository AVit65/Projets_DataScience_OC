# Portfolio Data Science | OpenClassrooms

## Présentation

Ce dépôt rassemble les neuf projets réalisés dans le cadre de ma formation **Data Scientist chez OpenClassrooms**.

Ces projets m'ont permis de travailler sur des problématiques variées, allant de l'exploration et de la préparation des données à la conception, l'évaluation et au déploiement de modèles prédictifs. Ils couvrent également le Deep Learning, le traitement du langage naturel, la vision par ordinateur, les environnements Big Data et le cadrage de projets d'intelligence artificielle.

Chaque projet s'appuie sur un contexte métier spécifique et mobilise une démarche analytique visant à transformer des données en résultats interprétables et exploitables pour la prise de décision.

---

## 📂 Projets réalisés

### 📊 [Projet 2 : Analyse de données éducatives](./OC_P02_Analysez-des-donnees-de-systemes-educatifs/)

**Analyse exploratoire | Python | Statistiques | Data Visualisation**

La start-up Academy souhaite évaluer les opportunités d'un développement international de ses formations en ligne. Ce projet consiste à explorer les données éducatives de la Banque mondiale afin d'évaluer leur qualité, d'identifier les indicateurs pertinents et de comparer le potentiel des différents pays.

Les travaux comprennent l'analyse des valeurs manquantes, l'exploration statistique des indicateurs, l'étude des évolutions temporelles et des disparités géographiques, ainsi que la construction d'un classement des pays.

### 🧹 [Projet 3 : Préparation de données pour un organisme de santé publique](./OC_P03_Preparez-des-donnees-pour-un-organisme-de-sante-publique/)

**Data Cleaning | Analyse exploratoire | Statistiques multivariées | ACP**

Santé publique France souhaite améliorer la qualité des informations présentes dans la base collaborative Open Food Facts. Le projet vise à identifier et traiter les incohérences, les valeurs manquantes et les anomalies afin d'étudier la faisabilité d'un système de suggestion ou d'autocomplétion des données.

Les travaux mobilisent des techniques de nettoyage, des analyses statistiques univariées et multivariées, l'étude des corrélations et l'analyse en composantes principales.

### 🏢 [Projet 4 : Prédiction des besoins énergétiques des bâtiments](./OC_P04_Anticipez-les-besoins-energetiques-de-batiments/)

**Machine Learning supervisé | Régression | Feature Engineering | Interprétabilité**

La ville de Seattle souhaite anticiper les consommations énergétiques et les émissions de gaz à effet de serre de ses bâtiments non résidentiels.

Ce projet consiste à développer et comparer plusieurs modèles de régression à partir des caractéristiques structurelles des bâtiments. Il comprend la préparation des données, le feature engineering, l'optimisation des modèles, leur évaluation par validation croisée et l'analyse de leurs prédictions. Une étude spécifique évalue également l'apport du score ENERGY STAR aux performances prédictives.

### 👥 [Projet 5 : Segmentation des clients d'un site e-commerce](./OC_P05_Segmentez-des-clients-d-un-site-e-commerce-main/)

**Machine Learning non supervisé | Clustering | Segmentation client | Stabilité temporelle**

La plateforme brésilienne Olist souhaite mieux comprendre les comportements d'achat de ses clients afin de personnaliser ses campagnes marketing.

Après l'agrégation de plusieurs sources de données, des indicateurs clients sont construits pour caractériser les comportements d'achat. Plusieurs algorithmes de clustering sont ensuite comparés afin d'identifier des segments homogènes et interprétables. Une analyse de la stabilité temporelle des clusters permet enfin de proposer une stratégie de maintenance de la segmentation.

### 🖼️ [Projet 6 : Classification automatique de produits e-commerce](./OC_P06_Classifiez-automatiquement-des-biens-de-consommation-main/)

**Deep Learning | Computer Vision | NLP | Classification d'images**

Une marketplace souhaite automatiser la catégorisation de ses produits à partir des descriptions textuelles et des images fournies par les vendeurs.

Le projet débute par une étude de faisabilité mobilisant des techniques de traitement du langage naturel, d'extraction de caractéristiques et de réduction de dimension. Il se poursuit par le développement et l'évaluation de modèles de classification d'images, avec une analyse des performances, des courbes d'apprentissage et des erreurs de prédiction.

### 💳 [Projet 7 : Développement et déploiement d'un outil de scoring de crédit](https://github.com/AVit65/OC_P7_Implementer_un_outil_de_scoring)

**Machine Learning | Scoring | SHAP | MLOps | API | Streamlit**

La société financière Prêt à Dépenser souhaite automatiser l'évaluation du risque associé aux demandes de crédit à la consommation.

Le projet couvre l'ensemble du cycle de développement d'un modèle prédictif, depuis la préparation des données jusqu'à son déploiement. Plusieurs modèles de classification sont entraînés et optimisés, avec une attention particulière portée au choix du seuil de décision et à l'interprétabilité des prédictions grâce à SHAP.

Le modèle est ensuite intégré dans une API et un dashboard interactif destiné aux conseillers financiers. Le projet comprend également le suivi des expérimentations avec MLflow, des tests automatisés, un processus de déploiement continu et une analyse de dérive des données.

**Applications déployées :**

- [Consulter le dashboard interactif](https://oc-p7-cu77.onrender.com/)
- [Consulter la documentation de l'API](https://api-oc-p7.onrender.com/docs#/)

### 🔬 [Projet 8 : Dashboard et veille technologique en intelligence artificielle](./OC_P08_Realisez-un-dashboard-et-assurez-une-veille-technique-main/)

**Data Visualisation | Explicabilité | Deep Learning | Veille technologique**

Ce projet comprend deux volets complémentaires.

Le premier prolonge le projet 7 avec le développement d'un tableau de bord permettant aux conseillers financiers de consulter les scores de risque et de comprendre les facteurs influençant les prédictions.

Le second prolonge le projet 6 à travers une veille technologique consacrée aux méthodes de classification d'images. De nouvelles approches sont étudiées, implémentées et comparées aux modèles précédemment développés. Les résultats sont synthétisés dans une note méthodologique présentant les avantages, les limites et les performances des méthodes évaluées.

### ☁️ [Projet 9 : Traitement distribué de données dans le Cloud](./OC_P09_Realisez-un-traitement-dans-un-environnement-Big-Data-sur-le-Cloud-main/)

**Big Data | Cloud Computing | Traitement distribué | Extraction de caractéristiques | PCA**

La start-up AgriTech Fruits! souhaite développer une application mobile capable d'identifier des fruits à partir de photographies.

Le projet consiste à concevoir une chaîne de traitement d'images comprenant le prétraitement, l'extraction de caractéristiques et la réduction de dimension. Après une première validation locale, cette chaîne est adaptée à un environnement Big Data reposant sur Amazon EMR afin de permettre son exécution sur des volumes de données plus importants.

### 🤖 [Projet 10 : Cadrage d'un projet d'intelligence artificielle](./OC_P10_Realisez-le-cadrage-d-un-projet-IA-main/)

**Gestion de projet IA | Agile Scrum | Analyse des risques | RGPD | Étude de rentabilité**

L'entreprise Fashion-Insta souhaite développer une application de recommandation vestimentaire personnalisée à partir de photographies fournies par ses utilisateurs.

Ce projet consiste à réaliser le cadrage fonctionnel, technique, organisationnel et financier de l'application. Il comprend l'analyse des besoins utilisateurs, la rédaction des user stories, la planification des sprints selon la méthodologie Agile Scrum, l'identification des ressources nécessaires et l'estimation des coûts et des gains attendus.

Une attention particulière est portée à l'analyse des risques techniques, juridiques et éthiques, notamment à la protection des données personnelles et à la transparence des recommandations.

---

## 🛠️ Compétences mobilisées

| Domaine | Compétences et méthodes |
|---|---|
| **Programmation et analyse** | Python, pandas, NumPy, Jupyter Notebook, préparation et exploration de données |
| **Statistiques** | Statistiques descriptives et inférentielles, analyses multivariées, corrélations, ACP |
| **Machine Learning supervisé** | Régression, classification, scoring, feature engineering, validation croisée, optimisation des modèles |
| **Machine Learning non supervisé** | Clustering, segmentation, réduction de dimension, analyse de stabilité |
| **Deep Learning** | Classification d'images, réseaux de neurones convolutifs, extraction de caractéristiques |
| **NLP et Computer Vision** | Prétraitement de textes et d'images, représentation des données non structurées |
| **Évaluation et interprétabilité** | Métriques de performance, analyse des erreurs, SHAP, explicabilité des prédictions |
| **MLOps et déploiement** | MLflow, API, Streamlit, GitHub Actions, tests automatisés, suivi de la dérive des données |
| **Big Data et Cloud** | Amazon EMR, traitements distribués, stockage Cloud |
| **Gestion de projet IA** | Agile Scrum, user stories, planification, analyse des risques, RGPD, estimation des coûts |

---

## 📁 Organisation du dépôt

Chaque projet est organisé dans un dossier indépendant comprenant, selon les cas :

- **README.md** : présentation détaillée du contexte, des objectifs et de la démarche.
- **Notebook/** : notebooks d'analyse, de préparation et de modélisation.
- **Output/**  : résultats, tableaux et visualisations produits au cours des analyses.
- **Soutenance/** : supports de présentation du projet.
- **Requirements** : dépendances nécessaires à l'exécution du code.
- **Autres dossiers spécifiques** : scripts, configurations, API, dashboard ou ressources Cloud.

Les jeux de données volumineux et certains modèles entraînés ne sont pas systématiquement inclus dans les dépôts. Les sources des données et les modalités d'accès sont précisées dans les README individuels.

---