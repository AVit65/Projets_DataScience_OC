📊 **Projet**

Pour atteindre son objectif de ville neutre en émissions de carbone en 2050, la ville de Seattle souhaite modéliser les consommations énergétiques ainsi que les émissions en gaz à effet de serre des bâtiments non destinés à l’habitation. L'objectif principal de ce projet est donc de développer un modèle de prédiction de ces deux variables à partir de données structurelles liées aux batiments. Il sera aussi important d'évaluer l'impact de la variable ENERGYSTAR sur les performances prédictives afin de déterminer s'il est pertinent de continuer à calculer ce score qui est fastidieux à calculer.

🎓 **Compétences évaluées**
- Créer les variables pertinentes d'un modèle d'apprentissage supervisé ou non-supervisé
- Sélectionner, entraîner et évaluer des modèles d’apprentissage supervis


📂 **Architecture du repository**

*Note*: les données ne sont pas inclues et doivent être téléchargés via le lien ci-dessous

```
OC_P4_Anticipez-les-besoins-énergétiques-de-batiments
│
├── Data/                       
├── Notebook/                         
│   ├── Notebook_1_Analyse_exploratoire.ipynb    # Notebook contenant l'analyse exploratoire, le nettoyage et le feature engineering     
│   ├── Notebook_2_Modelisation_emissions.ipynb  # Notebook de la modélisation des émissions en gaz à effet de serre
│   ├── Notebook_3_Modelisation_energie.ipynb    # Notebook de la modélisation des consommations énergétiques
├── Ouput/                                    
│   ├── Analyses exploratoires/  
│   │    ├── Analyses bivariées                   # Graphiques issus des analyses bivariées
│   │    ├── Corrélations                         # Heatmap représentant les corrélations entre variables
│   │    ├── Distribution                         # Distributions des variables brutes et construites
│   │    ├── Table                                # Table de données finale 
│   ├── Modélisation/  
│   │    ├── Analyse des erreurs                  # Graphiques représentant les erreurs de modélisation
│   │    ├── Explicativité                        # Graphiques de l'analyse explicative du modèle selectionné
│   │    ├── Optimisation                         # Graphiques de comparaison de modèles/nombre features
│   │    ├── Score de validation croisée          # Distributions des scores obtenus en validation croisée
├── Soutenance/                                   # Présentation en pdf
├── README.md                                     # Documentation générale du projet
├── Requirements                                  # Liste des dépendances nécessaires

```

🗄️ **Données**

La table de données brute  utilisée dans le notebook d’analyse  peuvent être téléchargées via ce [lien](https://data.seattle.gov/Built-Environment/Building-Energy-Benchmarking-Data-2015-Present/teqw-tu6e/about_data).

