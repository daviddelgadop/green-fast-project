# Projet Green & Fast 2026 — Optimisation des livraisons

## 1. Introduction du projet

Ce projet s’inscrit dans le cadre du module Data & Intelligence Artificielle.

Il vise à répondre à une problématique réelle d’optimisation logistique pour l’entreprise Eco-Delivery, spécialisée dans la livraison de repas à faible impact environnemental.

Promesse :
"Livré en 30 minutes, ou c’est offert, avec 0g de CO2 émis"

Problèmes identifiés :
- Livreurs se déplaçant à vide
- Mauvaise répartition géographique
- Retards de livraison
- Empreinte carbone trop élevée

Objectif : proposer une solution data permettant d’optimiser les livraisons.

---

## 2. Objectifs

### Objectifs métier

- Prédire les zones de forte demande
- Optimiser le positionnement des livreurs
- Réduire le temps de livraison
- Diminuer les trajets inutiles
- Améliorer la rentabilité

### Objectifs techniques

- Construire un pipeline de données
- Nettoyer et transformer les données
- Développer un modèle baseline
- Évaluer les performances
- Produire un MVP

---

## 3. Données

Dataset :
https://www.kaggle.com/datasets/gauravmalik26/food-delivery-dataset

Contenu :
- Données de commandes
- Informations livreurs
- Temps de livraison

---

## 4. Méthodologie

1. Compréhension du problème
2. Analyse exploratoire (EDA)
3. Nettoyage des données
4. Feature engineering
5. Modélisation
6. Évaluation
7. Itérations

---

## 5. Pipeline de données

- Nettoyage
- Transformation
- Encodage
- Split train/test
- Pipeline reproductible

---

## 6. Modélisation

- Régression linéaire
- Random Forest

---

## 7. Évaluation

- MAE
- RMSE

---

## 8. Organisation Agile

### Kanban
- À faire
- En cours
- Terminé

### Backlog
- Nettoyage données
- Modélisation
- Évaluation

### Definition of Done
- Code fonctionnel
- Code relu
- Résultat validé
- Versionné

---

## 9. Outils

- Python
- Pandas
- Scikit-learn
- Matplotlib / Seaborn
- Git

---

## 10. Installation et exécution

Prérequis :
Python 3.9+, pip, Git

Vérification :
python --version
pip --version
git --version

Cloner :
git clone https://github.com/daviddelgadop/green-fast-project.git
cd green-fast-project

Créer environnement :
python -m venv venv
venv\\Scripts\\activate

Installer dépendances :
pip install -r requirements.txt

Dataset :
data/train.csv

Lancer :
jupyter notebook

---

## 11. Vérification

- Dataset chargé
- Pipeline exécuté
- Modèle entraîné
- Métrique affichée

---

## 12. Problèmes fréquents

- Module manquant → pip install
- Mauvais chemin → vérifier data/train.csv

---

## 13. Version Python

Python 3.9+

---

## 14. Conclusion

Projet MVP combinant data engineering, machine learning et méthodologie Agile.