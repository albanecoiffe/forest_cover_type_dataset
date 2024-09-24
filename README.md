## Lab 2.2 : Classification Multi-Classes avec Régression Logistique One-vs-All et k-Nearest Neighbors sur le Dataset Forest Cover Type 🌲    

(Notebook)[]

Objectif :    
Ce projet a pour but de classifier les types de couvertures forestières en utilisant deux algorithmes de machine learning : la régression logistique One-vs-All et l'algorithme des k-Nearest Neighbors (k-NN). Le dataset utilisé est le Forest Cover Type Dataset de l'UCI Machine Learning Repository. Avant de procéder à la classification, une analyse exploratoire des données est réalisée à l'aide de ydata_profiling.

## 📊 Description du Dataset   
**Nom** : Forest Cover Type Dataset      
**Classes** : 7 types de couvertures forestières (Spruce/Fir, Lodgepole Pine, etc.)      
**Caractéristiques** : 54 attributs cartographiques (élévation, pente, type de sol, etc.)         
**Taille** : 581 012 échantillons         
 
## ⚙️ Phases du Projet      
**Profiling du Dataset avec ydata_profiling :**      
Génération d'un rapport de profil pour explorer le dataset (valeurs manquantes, outliers, corrélations, etc.). 

**Prétraitement des Données :**      
Ingénierie des caractéristiques, division du dataset en ensembles d'entraînement et de test (80/20), et standardisation des données pour améliorer la convergence des modèles.    

**Entraînement et Évaluation des Modèles :**          
- Régression Logistique One-vs-All :            
Entraînement du modèle avec la stratégie One-vs-All et évaluation des performances via matrice de confusion et rapport de classification.
   
- k-Nearest Neighbors (k-NN) :            
Entraînement du modèle k-NN et évaluation similaire à celle de la régression logistique.

**Analyse et Discussion :**      
- Comparaison des performances des deux modèles.           
- Exploration des hyperparamètres (ex. : différentes valeurs de k pour k-NN et ajustement de la régularisation pour la régression logistique).         
- Utilisation de la validation croisée pour une évaluation plus robuste.         

## 🛠️ Technologies Utilisées         
- `Python` : Langage de programmation pour l'analyse et la modélisation.      
- `Pandas et NumPy` : Manipulation et traitement des données.      
- `Matplotlib et Seaborn` : Visualisation des données et des résultats.      
- `scikit-learn` : Implémentation des modèles de machine learning.      
- `ydata_profiling` : Génération de rapports d'exploration de données.      
