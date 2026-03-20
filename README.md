## 11. Installation et exécution du projet

### 1. Cloner le repository

git clone https://github.com/TON-USERNAME/green-fast-project.git
cd green-fast-project

---

### 2. Créer un environnement virtuel

#### Sur Windows

python -m venv venv
venv\Scripts\activate

#### Sur Mac / Linux

python3 -m venv venv
source venv/bin/activate

---

### 3. Installer les dépendances

Si un fichier requirements.txt est fourni :

pip install -r requirements.txt

Sinon, installer manuellement :

pip install pandas numpy scikit-learn matplotlib seaborn jupyter

---

### 4. Télécharger le dataset

Télécharger le dataset depuis Kaggle :
https://www.kaggle.com/datasets/gauravmalik26/food-delivery-dataset

Placer le fichier train.csv dans le dossier :

data/train.csv

Structure attendue du projet :

green-fast-project/
│
├── data/
│   └── train.csv
│
├── notebooks/
│   └── green_fast_mvp.ipynb
│
├── src/
│   └── pipeline.py (si utilisé)
│
├── requirements.txt
└── README.md

---

### 5. Lancer le projet

#### Option 1 — Notebook (recommandé)

jupyter notebook

Puis ouvrir :

notebooks/green_fast_mvp.ipynb

Exécuter les cellules dans l’ordre.

---

#### Option 2 — Script Python (si présent)

python src/pipeline.py

---

### 6. Vérification du bon fonctionnement

Le projet fonctionne correctement si :

- Les données sont chargées sans erreur
- Le pipeline s’exécute jusqu’au bout
- Un modèle est entraîné
- Une métrique (MAE ou RMSE) est affichée

---

### 7. Problèmes fréquents

- Erreur "ModuleNotFoundError" → vérifier installation avec pip
- Erreur de chemin fichier → vérifier data/train.csv
- Problème Kaggle → vérifier que le fichier est bien téléchargé

---

### 8. Version Python recommandée

Python 3.9 ou supérieur