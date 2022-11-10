# Prediction-Analysis
This project was completed within the framework of the Data Analytics program with BlackTECH Academy

# Problem
The Analytics team has been tasked to help the Collections team in the borrowers that are rolling
forward from an early due stage to later due stages. For that you are given a dataset that contains
customers that have been in an early due stage (1-30 days delinquent) and some of their main attributes.
Your task:
a) Predict whether the loan rolled or not rolled
b) What is your prediction accuracy

# Dataset
![image](https://user-images.githubusercontent.com/107350001/190902448-98b2ebc9-9ae8-4d42-836b-ae9d2f3c1121.png)

# VERSION FRANCAISE
L'équipe d'analytique a été chargée d'aider l'équipe de recouvrement à identifier les emprunteurs qui passent d'un stade d'échéance précoce à un stade d'échéance plus avancé. Pour cela, j’ai été donné un ensemble de données qui contient des clients qui ont été dans une phase d'échéance précoce (1-30 jours de retard) et certains de leurs principaux attributs. Ma tâche est de prédire si le prêt a été prorogé ou non, et d’estimer la précision de ma prédiction.
Pour se faire, j’ai procédé au chargement des données (provenant d’un fichier .csv) dans le logiciel Jupyter Notebook afin d’utiliser le langage python. Il s’agit d’un base de données sur 5783 clients et 10 variables. En suite, je l’ai nettoyé en éliminant les duplications, les valeurs manquants et les erreurs. Puis j’ai fait une analyse descriptive de chaque variable, ainsi que tester la corrélation entre les variables dépendants et les variables indépendants. A base des plus pertinents relations de dépendance entre ceux-ci, j’ai conçue un modèle et en suite je l’ai entraîné. Après plusieurs essaies, j’ai conclue que le modèle RandomForestClassifier était le meilleur avec une précision de 79%. Ma conclusion est que  le prêt n’a pas été prorogé.
