📊 **Projet**

L’agence Santé publique France souhaite améliorer la qualité de la base Open Food Facts, une base collaborative recensant des informations détaillées sur les produits alimentaires. Le remplissage manuel de nombreux champs lors de l’ajout d’un produit engendre des erreurs, des incohérences et des données manquantes. Le projet vise à nettoyer, structurer et analyser les données existantes afin d’identifier ces problèmes. L’objectif final est de développer un système intelligent de suggestion ou d’auto-complétion pour faciliter la saisie et améliorer la qualité globale de la base.

🎓 **Compétences évaluées**
- Déterminer les objectifs du nettoyage des données et de la démarche de mise en œuvre
- Effectuer des analyses statistiques univariées et multivariées
- Effectuer des opérations de nettoyage sur des données structurées
- Représenter des données grâce à des graphiques afin justifier les analyses réalisées


📂 **Architecture du repository**

*Note*: les données ne sont pas inclues et doivent être téléchargés via le lien ci-dessous

```
OC_P2_Preparez-des-donnees-pour-un-organisme-de-sante/
│
├── Data/                       
├── Notebook/                         # Notebook d’analyse                            
├── Ouput/                                    
│   ├── Analyses_bivariées/           # Distribution des variables explicatrices en fonction de la variable cible
│   ├── Corrélation/                  # Heatmap illustrant les corrélation entre variables 
│   ├── PCA/                          # Graphique des éboulies, cercles de corrélations et projections
│   ├── Table/                        # Tableau 
├── Soutenance/                       # Présentation en pdf
├── README.md                         # Documentation générale du projet
├── Requirements                      # Liste des dépendances nécessaires

```

🗄️ **Données**

La table de données brute  utilisée dans le notebook d’analyse  peuvent être téléchargées via ce [lien](https://s3-eu-west-1.amazonaws.com/static.oc-static.com/prod/courses/files/parcours-data-scientist/P2/fr.openfoodfacts.org.products.csv.zip) .

