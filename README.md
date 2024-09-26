## Description du projet

Ce projet vise à simuler une **équation de réaction-diffusion** bistable pour segmenter les images satellites radar (SAR) et détecter des zones de neige. L'algorithme utilise un **schéma aux différences finies** pour résoudre l'équation de réaction-diffusion. 

L'objectif principal est de délimiter des zones de neige à partir d'images radar et de comparer ces résultats à des **mesures optiques satellitaires** pour vérifier la précision de la méthode de segmentation.

## Contexte scientifique

L'équation de réaction-diffusion étudiée est bistable, c'est-à-dire qu'elle possède deux états d'équilibre spatialement homogènes. Cette caractéristique est utilisée dans le cadre de la **segmentation d'image** pour identifier des zones distinctes de neige et de non-neige sur des images SAR.

## Structure du projet

- **Algorithme principal** : Simulation de l'équation de réaction-diffusion par un schéma aux différences finies.
- **Images satellites** : Données SAR utilisées pour la segmentation des zones de neige.
- **Comparaison des résultats** : Les résultats obtenus sont comparés à des images optiques satellites afin d'évaluer la pertinence de la méthode.

## Installation

Pour exécuter ce projet, il est nécessaire d'installer les bibliothèques suivantes :

- \`numpy\` : Pour les calculs numériques.
- \`matplotlib\` : Pour la visualisation des résultats.
- \`scipy\` : Pour les méthodes numériques (si nécessaire).
- **Bibliothèques spécifiques** aux données d'images satellites (ex: \`GDAL\` pour la manipulation des données SAR).

Vous pouvez installer ces dépendances via pip :

\`\`\`bash
pip install numpy matplotlib scipy gdal
\`\`\`

## Utilisation

1. **Simulation de l'équation et segmentation d'image** : Tout le code et les résultats sont regroupés dans le notebook Jupyter \`reaction_diffusion_neige.ipynb\`. Vous pouvez exécuter le notebook pour :
   - Simuler l'équation de réaction-diffusion.
   - Appliquer l'algorithme sur les images SAR pour segmenter les zones de neige.
   - Visualiser les résultats et les comparer aux données optiques satellitaires.

2. **Exécution du notebook** : 
   - Ouvrez le notebook \`reaction_diffusion_neige.ipynb\` avec Jupyter Notebook ou Jupyter Lab.
   - Exécutez chaque cellule pour reproduire les résultats de la simulation et de la segmentation.

## Résultats attendus

L'algorithme doit être capable de segmenter efficacement les zones de neige et non-neige. La comparaison avec les données optiques fournira une validation des résultats obtenus à partir des images radar.

## Auteurs

- **Hamza Aboutni** - Étudiant en ingénierie financière à Ensimag .
- **Belharir Khalil** -Élève en ingénieurie financière à Ensimag .

