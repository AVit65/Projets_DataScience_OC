📊 **Projets**

Ce projet se compose de deux sous-projets indépendants.

Le premier sous-projet fait suite au projet n°7, dont l’objectif était d’implémenter un outil de scoring pour une société financière. Cette nouvelle étape consiste à développer un dashboard interactif destiné à assister les conseillers financiers de la société dans la prise de décision d’octroi de prêt. Le tableau de bord développé leur permet à la fois de visualiser le score de risque d’un client et d’expliquer les décisions du modèle. Le code associé à ce projet est disponible dans le dépôt du projet n°7, accessible via ce [lien](https://github.com/AVit65/OC_P7_Implementer_un_outil_de_scoring)
.

Le second sous-projet fait suite projet n°6, qui portait sur le développement d’un moteur de classification de produits pour une plateforme de vente en ligne. Lors de ce premier travail, plusieurs approches et architectures de réseaux de neurones convolutifs ont été évaluées. La suite du projet consiste à mettre en place une veille technologique afin d’explorer des méthodes plus récentes, de les implémenter et de les comparer aux approches précédemment testées. Une note méthodologique a été rédigée, afin de présenter la nouvelle approche proposé, ses avantages et ses limites, ainsi qu’une comparaison détaillée des performances et des résultats obtenus.

🎓 **Compétences évaluées**
- Réaliser la présentation orale d’une démarche de modélisation à un client interne/externe
- Réaliser une veille sur les outils et tendances en data science et IA
- Réaliser un tableau de bord afin de présenter son travail de modélisation à un public
- Rédiger une note méthodologique afin de communiquer sa démarche de modélisation


📂 **Architecture du repository**

*Note 1*: les données ne sont pas inclues et doivent être téléchargées via le lien ci-dessous

*Note 2*: les modèles ne sont pas inclus non plus. 

```
OC_P8_Realisez-un-dashboard-et-assurez-une-veille-technique/
│
├── Data/                       
├── Notebook/                            # Notebook d’analyse   
├── Note_methodologique/                 # Note méthodologique                           
├── Ouput/                                    
│   ├── Comparaison_modèles/             # Notebook d’étude de classification et d'explicativité
│   ├── Courbes_d'apprentissage/         # Graphiques représentant les courbes d'apprentissages des modèles
│   ├── Erreur_classification/           # Visualisation des erreurs de classification
│   ├── Explicativité/                   # Figure issue de l'analyse d'explicativité du modèle retenu
│   ├── Matrice_de_confusion/            # Matrice de confusions générées pour évaluer les modèles 
│   ├── Optuna/                          # Objet contenant les résultats d'optimisation des hyperparamètres avec Optuna
│   ├── Table/                           # Table de données et de résultats
├── Soutenance/                          # Présentation en pdf
├── README.md                            # Documentation générale du projet
├── Requirements                         # Liste des dépendances nécessaires

```

🗄️ **Données**

La table de données brute  utilisée dans le notebook d’analyse ainsi que les images traitées peuvent être téléchargées via ce [lien](https://s3-eu-west-1.amazonaws.com/static.oc-static.com/prod/courses/files/Parcours_data_scientist/Projet+-+Textimage+DAS+V2/Dataset+projet+pre%CC%81traitement+textes+images.zip)

