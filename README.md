# Notebooks, présentation pour le projet de déploiement d'un modèle dans le cloud

## Description
### Le contexte : 
Fruits! est une start-up de l’AgriTech qui souhaite proposer des solutions innovantes pour la récolte des fruits. Son concept : Développer des robots cueilleurs intelligents pour préserver la biodiversité des fruits en permettant des traitements spécifiques.
### Objectif : 
Se faire connaître en mettant à disposition une app mobile pour que les users (grand public) puisse obtenir des informations sur le fruit pris en photo. 

### Solution :  
Mise en place d’une première version du moteur de classification des images de fruits, d’une première version de l’architecture Big Data nécessaire.

### Les données à disposition : DataSet Kaggle Fruits 360 :
Source du jeu de données : Kaggle
Type de données = Images de fruits et de légumes sur fond blanc, sous différents angles, extraites de vidéos de type timelapse
Configuration du dossier : chaque variété est un dossier qui comporte les photos de ladite variété
Type d’images = JPG 100 x 100 
Taille du dataset utilisé : 22688 images 

### La mission :
- Créer un environnement Big Data sur Amazon Web Services avec S3, EMR, IAM
- Réaliser une chaîne de traitement des images dans l'environnement à l'aide de PySpark

## Découpage des dossiers
- Notebooks/  
  - fichier_csv_complet.csv #fichier csv qui reprend pour chaque image les features retenues suite au traitement des images ainsi que le label associé
  - Guarneri_Naomi_1_notebook_fruits_pyspark_072023-TEST_COMPLET.ipynb #notebook de traitement d'images PySpark
  - Guarneri_Naomi_8_presentation_072023.pdf #présentation du travail effectué dans le projet
  - README.md # fichier descriptif
