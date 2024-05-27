# Projet de Reconnaissance Optique de Caractères (OCR)

## Description
Ce projet comprend l'utilisation de techniques avancées de reconnaissance optique de caractères pour extraire des informations à partir d'images de cartes et de données tabulaires. Le projet est divisé en deux parties principales, traitées dans deux fichiers Jupyter distincts :

### Fichiers Jupyter

- **map.ipynb**: Ce notebook implémente et démontre l'extraction de texte à partir d'images de cartes en utilisant l'API Google Cloud Vision. Le notebook traite les images, identifie et regroupe les textes basés sur leur proximité spatiale, et extrait des informations structurées sous forme de JSON.

- **tabular_data.ipynb**: Ce fichier traite des données tabulaires complexes en utilisant le package OCR de Nanonets. Il démontre la capacité de lire et de convertir des données tabulaires en un format manipulable et lisible. Les résultats sont présentés dans **tabular_data.xlsx**.

## Méthodes Explorées

### Pour les images standards :
- **API Google VISION OCR** : Utilisée pour identifier et extraire le texte des images de carte.
- **Tesseract OCR avec des méthodes d'extraction basées sur EAST et CRAFT** : Testées pour leur efficacité à détecter et reconnaître le texte dans des conditions variées.

### Pour les images tabulaires :
- **DONUT** : Un modèle de deep learning spécifiquement conçu pour reconnaître et interpréter les structures des tableaux complexes.
- **Package OCR de Nanonets** : Utilisé pour extraire efficacement le texte et les données des tableaux à partir des images et des fichiers PDF.

## Installation des Dépendances

Pour configurer l'environnement nécessaire à l'exécution des notebooks, veuillez installer les dépendances suivantes :


pip install ocr-nanonets-wrapper
pip install google-cloud-vision
