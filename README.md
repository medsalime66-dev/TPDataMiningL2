# Pipeline KDD pour le Data Mining

## Description
Ce projet implémente la première étape du processus **KDD (Knowledge Discovery in Databases)** : l'acquisition des données.

L'objectif est de collecter des données provenant de plusieurs sources et de les fusionner dans un seul **DataFrame Pandas** afin de faciliter leur analyse.

---

## Sources de Données

Le projet utilise plusieurs sources de données :

- Dataset CSV (Student Performance)
- Dataset JSON
- Dataset Excel
- Base de données MySQL
- API publique
- Web scraping

---

## Technologies Utilisées

Les technologies et bibliothèques utilisées dans ce projet sont :

- Python
- Pandas
- SQLAlchemy
- MySQL
- Requests
- BeautifulSoup

---

## Structure du Projet


```
Projet_DataMining/
│
├── data/
│   ├── student-mat.csv
│   ├── movies.json
│   └── airline_data.xlsx
│
├── notebooks/
│   └── pipeline.ipynb
│
├── src/
│
├── requirements.txt
└── README.md
```


---

## Installation

Pour installer les bibliothèques nécessaires au projet, exécutez la commande suivante :
pip install -r requirements.txt


---

## Exécution du Notebook

Pour exécuter le projet, ouvrez le notebook :

notebooks/pipeline.ipynb

Ensuite, exécutez les cellules une par une pour réaliser le pipeline d'acquisition des données.

---

## Auteur

Projet de Data Mining – Pipeline KDD
