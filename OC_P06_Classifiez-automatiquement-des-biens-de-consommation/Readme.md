📊 **Projet**

L'entreprise place de marché est une société anglophone spécialisée dans la vente de produits en ligne. Elle met en relation des vendeurs proposant des articles à la vente et des acheteurs répartis dans différents pays.
Actuellement, la catégorisation des produits disponibles sur la plateforme est effectuée manuellement par les vendeurs. Ce processus, peut donc être sujet à des erreurs de saisie ou de subjectivité. Dans ce contexte, l’entreprise place de marché souhaite automatiser l’attribution des catégories produits afin d’optimiser ses processus et d’améliorer la qualité de la classification. Elle nous sollicite pour évaluer la faisabilité d’un système de classification automatique des produits, basé sur deux types de données fournies par les vendeurs:

- Les descriptions textuelles des produits en anglais
- Les images associées aux produits

À l’issue de cette étude, le projet s’est concentré sur le développement d’un modèle de classification basé sur les images des produits. 

🎓 **Compétences évaluées**
 - Définir la stratégie d’élaboration d’un modèle d'apprentissage profond
- Évaluer la performance des modèles d’apprentissage profond
- Prétraiter des données non structurées de type image
- Prétraiter des données non structurées de type texte
- Réaliser la collecte des données répondant à des critères définis via une API
- Réduire la dimension de données de grande dimension
- Utiliser des techniques appropriées de réduction en deux dimensions


📂 **Architecture du repository**

*Note 1*: les données ne sont pas inclues et doivent être téléchargées via le lien ci-dessous

*Note 2*: les modèles ne sont pas inclus non plus. 

```
O_OC_P6_Classifiez-automatiquement-des-biens-de-consommation/
│
├── Data/                       
├── Notebook/                            # Notebook d’analyse                            
├── Ouput/                                    
│   ├── Comparaison_modèles/             # Notebook d’étude de faisabilité et de classification
│   ├── Courbes_d'apprentissage/         # Graphiques représentant les courbes d'apprentissages des modèles
│   ├── Data_augmentation/               # Exemple d'images augmentées pour enrichir le dataset
│   ├── Erreur_classification/           # Visualisation des erreurs de classification
│   ├── Extraction_de_features_images/   # Figures issus de l'étape d'extraction de features des images 
│   ├── Extraction_de_features_texte/    # Figures issus de l'étape d'extraction de features des descriptions 
│   ├── Matrice_de_confusion/            # Matrice de confusions générées pour évaluer les modèles 
│   ├── Preprocessing_images/            # Figures issues de l'étape de prétraitement des images 
│   ├── Preprocessing_texte/             # Figures issues de l'étape de prétraitement des descriptions 
│   ├── Table/                           # Table de données et de résultats
├── Soutenance/                          # Présentation en pdf
├── README.md                            # Documentation générale du projet
├── Requirements                         # Liste des dépendances nécessaires

```

🗄️ **Données**

La table de données brute  utilisée dans le notebook d’analyse ainsi que les images traitées peuvent être téléchargées via ce [lien](https://s3-eu-west-1.amazonaws.com/static.oc-static.com/prod/courses/files/Parcours_data_scientist/Projet+-+Textimage+DAS+V2/Dataset+projet+pre%CC%81traitement+textes+images.zip)

