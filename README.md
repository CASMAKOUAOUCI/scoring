
#  Présentation
La mission principale de ce projet est de prédire le risque de faillite d'un client pour une société de crédit. Pour cela, nous devons configurer un modèle de classification binaire et d'en analyser les différentes métriques.

Ce projet consiste à créer une API web avec un Dashboard interactif. Celui-ci devra a minima contenir les fonctionnalités suivantes :

-   Permettre de visualiser le score et l’interprétation de ce score pour chaque client de façon intelligible pour une personne non experte en data science.
-   Permettre de visualiser des informations descriptives relatives à un client (via un système de filtre).
-   Permettre de comparer les informations descriptives relatives à un client à l’ensemble des clients ou à un groupe de clients similaires.

#  Construction

Dans ce dépôt, vous trouverez :

-    le Notebook Jupyter pour l'étude des données, l'entraînement et la configuration du modèle de classification et modèle retenue.
-    la note technique qui explique en détails la construction et les résultats du modèle.
-    la configuration locale de l'API, cette "version" de l'API s'appuie sur  app.py :
    -  contient la partie dashbaord codée avec Streamlit.
-    Cette version n'utilise que Streamlit qui a l'avantage d'être très simple à coder, et qui contient Pycharm, un serveur web de Flask.

## Modèle de classification
Le modèle retenu pour cet exercice est le modèle Régression logistic 
qui donne meilleur f-beta-score